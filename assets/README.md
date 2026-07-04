# assets/ (screenshots & demo GIFs)

This folder is intended to hold screenshot and demo GIF files for the README.

Recommended filenames (place these at repository root under `assets/`):

- `screenshot.png` — A static screenshot of the UI (recommended size: 800×450 or 1200×675)
- `demo.gif` — A short animated GIF (5–10 seconds) demonstrating creating a connection and exchanging messages. Keep the file size small (< 2–3 MB) for faster loading.

How to create a GIF (Linux/macOS):

1. Use Peek (GUI) or record with an internal screen recorder and convert to GIF with ffmpeg:
   - Record video (MP4) and convert:
     `ffmpeg -i demo.mp4 -vf "fps=10,scale=800:-1:flags=lanczos" -loop 0 demo.gif`

2. Commit the files:
   `git add assets/demo.gif assets/screenshot.png && git commit -m "Add demo assets" && git push`

Once added, the README will display the images in the Demo & Screenshots section.
