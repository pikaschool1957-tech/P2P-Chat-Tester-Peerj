# assets/ (screenshots & demo assets)

This folder previously held demo screenshots and animated GIFs referenced from the README. The README has been updated to remove direct image embeds for a leaner repository. The image files that used to be shown in the README have been replaced with small placeholder markers in the repository.

If you'd like these files removed from the repository entirely, I can delete them on request (I can do that next). To add screenshots or a short animated demo later, place them under `assets/` using the recommended filenames and formats below and update the README.

Recommended filenames:

- `screenshot.png` — A static screenshot of the UI (recommended size: 800×450 or 1200×675)
- `demo.gif` — A short animated GIF (5��10 seconds) demonstrating creating a connection and exchanging messages. Keep the file size small (< 2–3 MB) for faster loading.

How to add files and commit:

```bash
# add files
git add assets/screenshot.png assets/demo.gif
# commit
git commit -m "Add demo assets"
# push
git push
```
