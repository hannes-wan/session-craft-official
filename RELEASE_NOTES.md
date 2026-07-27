**Session Craft Community Edition is free to download and use.**

Session Craft 0.1.9 makes cold project playback responsive by preparing reusable decoded audio up front, reporting honest work progress, and recovering safely when saved stems are unavailable.

- Decoded playback now uses a singleflight cache and prewarms valid stems after separation or project load, so concurrent playback requests share one decode and warm playback starts without repeating six-stem work.
- Long-running separation, project loading, and first-play preparation now report determinate phase progress and reach completion only after playback data is ready, keeping the transport stable instead of appearing frozen or shifting.
- If saved stem files are missing, the live session falls back to the available full mix without exposing broken stem controls; saving the project still preserves the original stem references so they can recover when the files return.
