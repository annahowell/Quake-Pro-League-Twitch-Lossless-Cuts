# Quake Pro League (QPL) Twitch Video Lossless Cut Files

This repo contains Lossless cut .CSV files for the Quake Pro League video files available on Twitch, allowing you to prune the downtime between matches (where the 'Back in X minutes' screen appears). When possible the beginning of the video will also contain 10 seconds of each schedule screen. YouTube-DL and Lossless cut are open source and available for Linux, MacOS and Windows.

Be aware that this repo is not up to date, but I will add more .CSV files for each week as I go through my QPL archive. **Currently up to 2020-21 Stage 1 Week2**

## How to use these files
1. Install both YouTube-DL and [FFmpeg](https://github.com/FFmpeg/FFmpeg). How to do this is beyond the scope of this readme, but can be easily googled.

3. Look at [https://www.twitch.tv/quake](https://www.twitch.tv/quake) and determine the URL of the video.

4. Decide the quality you wish to keep: `youtube-dl -F https://www.twitch.tv/videos/472154353`  

5. Download 720p 60hz (for example) version: `youtube-dl -f 720p60 https://www.twitch.tv/videos/472154353`

6. Download and install [Lossless cut](https://github.com/mifi/lossless-cut/releases).

7. Open Lossless cut and then go to settings (the cog button top right) and ensure 'automerge exported files' and 'keyframe cut' are selected.

8. Open the QPL .mp4 you downloaded in Lossless cut.

9. Go to 'file' -> 'Load CSV' and load the appropriate .CSV from this repo and then click 'export'.  

**The QPL has misnamed some of their streams, so I renamed my copies locally. If you're in as to doubt which .CSV file corresponds to the video file, look at the number in the file, e.g: 472154353.**
