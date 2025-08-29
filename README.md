# Voice → To‑Do PoC (V1)

This is a proof‑of‑concept web app that lets you speak tasks (via browser SpeechRecognition API) 
and automatically add them to a to‑do list. Tasks can also be typed manually.

## How to Run
1. Download this project and unzip it.
2. Open `index.html` in a supported browser (Chrome/Edge recommended).
3. Allow microphone access when prompted.
4. Speak short tasks — they will appear in the to‑do list.
5. You can also type tasks manually in the input box.

## Project Structure
- `index.html` — main app (self‑contained: HTML, CSS, JS in one file).
- `tests/` — placeholder for future test scripts.
- `docs/` — placeholder for extended documentation.
- `assets/` — placeholder for images or additional assets.

## Notes
- This PoC uses the browser's `SpeechRecognition` (or `webkitSpeechRecognition`).
- Some browsers require HTTPS for microphone support.
- Tasks are stored locally in `localStorage`.
