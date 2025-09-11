# Draw 2 — PWA (Clean Localhost Build)

## Run locally (VS Code)
1. Open this folder in VS Code.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right‑click `index.html` → **Open with Live Server**.
4. Allow the camera.

## Features
- Mirrored video, drawing, and cursor (lime‑green circle; filled when pressed).
- Gestures (MediaPipe Hands):
  - **Closed peace (index+middle together)**: press/drag to draw; release on separation.
  - **Fist**: toggle Eraser ON/OFF (button + cursor “E” reflect state).
  - **Open hand**: cancels eraser.
- **Fill** tool (click to flood‑fill the clicked region) with “F” in cursor.
- Brushes: Round / Calligraphy / Pencil / Neon + **Styles** panel with fine sliders.
- Undo scrubber at top + Exit Undo.
- Clear row spaced to avoid mis‑clicks.
- Capture tray (10 max). Save with/without video backdrop.
- Signature (white transparent) bottom‑right (hidden during save/capture).
- CODE toggle (top‑left) shows diagnostics + fingertip overlay.

## Deploy to GitHub Pages
```bash
git init
git add .
git commit -m "Draw2 PWA clean build"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```
Then: Repo **Settings → Pages → Deploy from branch → main** (root). Open the Pages URL, allow camera.
