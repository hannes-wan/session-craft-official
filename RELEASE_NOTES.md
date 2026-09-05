**Session Craft Community Edition is free to download and use.**

Session Craft 0.1.10 fixes playback failing to start after stem separation when the audio device requires sample-rate conversion.

- First playback now waits for track preparation instead of incorrectly reporting a timeout after five seconds. Long songs may still need several seconds of preparation.
- Repeated Play requests reuse prepared playback, avoiding unnecessary repeated setup.
