# V4L2-CONTROL-SETTER

A Progressive Web App (PWA) for managing V4L2 (Video4Linux2) camera controls via a modern web interface.

## Features
- Adjust V4L2 camera controls (sliders, toggles, selectors)
- Responsive, standalone UI
- PWA: installable, offline support (manifest included)

## Getting Started
1. Clone this repository:
   ```sh
   git clone https://github.com/nemo2506/V4L2-CONTROL-SETTER.git
   ```
2. Open the project directory.
3. Serve the app with a static server (e.g. `http-server`, `python -m http.server`, or your preferred method):
   ```sh
   npx http-server .
   # or
   python -m http.server
   ```
4. Open your browser at `http://localhost:8080` (or the port shown).

## Usage: Install as App in Chrome
1. Open the app in Chrome (e.g. `http://localhost:8080`).
2. Click the install icon in the address bar (usually a computer with a down arrow) or open the Chrome menu (three dots) and select **Install V4L2-CONTROL-SETTER**.
3. The app will be installed and can be launched from your desktop or app launcher.

## PWA Support
- Includes `manifest.json` for installability
- Add your own service worker for offline support if needed

## Project Structure
- `index.html` – Main UI
- `app.js` – Application logic
- `manifest.json` – PWA manifest

## License
MIT
