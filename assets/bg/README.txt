Place small optimized looping background videos (mp4/webm) or gifs in the appropriate day/night subdirectory using these filenames for automatic use:

Day variations (place in /day folder):
- thunder.mp4    (daytime thunderstorm)
- rain.mp4       (daytime rain)
- snow.mp4       (daytime snow)
- fog.mp4        (daytime fog/mist)
- clear.mp4      (daytime clear sky)
- clouds.mp4     (daytime cloudy)

Night variations (place in /night folder):
- thunder.mp4    (nighttime thunderstorm)
- rain.mp4       (nighttime rain)
- snow.mp4       (nighttime snow)
- fog.mp4        (nighttime fog/mist)
- clear.mp4      (nighttime clear sky)
- clouds.mp4     (nighttime cloudy)

File size recommendations:
- Keep each loop <= 1-2 MB if possible (short, 2-6s loops) and encoded with H.264 or VP9.
- Prefer MP4 (H.264) or WebM for wide browser support. Name the files exactly as above to be automatically detected by the app.

If you don't provide these files, the app will fall back to hosted sample videos or images.

Example (PowerShell) to download a sample MP4 into this folder:

# from the project root (Terra)
Invoke-WebRequest -Uri "https://interactive-examples.mdn.mozilla.net/media/cc0-videos/flower.mp4" -OutFile ".\assets\bg\rain.mp4"

Replace with your own optimized loops for production.