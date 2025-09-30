# Pallet Tracker — Auto OCR + Camera (A–Z bins)

**What’s new**
- Live camera capture with `getUserMedia` (rear camera by default) + **auto OCR → parse → import**.
- File upload also supported; both paths auto-import recognized moves.
- Bins now accept **A–Z letters, digits, and dashes** anywhere (1–32 chars). Examples: `ZR-01-7`, `MEZZ-12`, `A-10-4`.

**Use it**
1. Open `index.html` in Chrome/Edge/Firefox (mobile or desktop).
2. Tap **Capture & Scan** (or upload a photo). When OCR finishes, valid rows are added automatically.
3. Manual add still works. Data is stored locally; export CSV anytime.

**Deploy**
- Drop `index.html` into a GitHub Pages repo (root), enable Pages, done.
