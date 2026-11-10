# BODYCAM: Operation Forest Shadow

A browser-based first-person tactical shooter built with **HTML, CSS, JavaScript, and Three.js**. Explore an abandoned forest installation, engage hostile patrols, clear the compound, and recover the intel.

## Play

Open `index.html` in a modern browser, or serve this directory with any static HTTP server. There is no build step or package installation. The game loads Three.js r128 from cdnjs, so an internet connection is required.

1. Clone or download this repository.
2. Open `index.html` (or visit the directory through a local static server).
3. Press **PLAY** and allow audio and pointer lock when prompted.

## Controls

### Desktop

| Action | Control |
| --- | --- |
| Move | W / A / S / D |
| Look | Mouse |
| Fire | Left mouse button |
| Aim | Hold right mouse button |
| Reload | R |
| Crouch | C |
| Jump | Space |
| Interact / take intel | E |
| Pause | Esc |

Click the game to capture the mouse. Press Esc to release it and pause.

### Touch devices

Play in **landscape orientation**. Use the left virtual joystick to move and drag on the right side of the screen to look around. On-screen buttons provide fire, aim, reload, crouch, jump, interact, and pause.

Open **Settings → Customize Controls** to reposition and resize touch controls, adjust opacity and spacing, then save or reset the layout. The layout is stored locally in that browser.

## Mission

1. Follow the road north to reach the installation.
2. Eliminate the hostiles in and around the compound.
3. Once the area is clear, enter the hangar and recover the intel.

Enemies patrol, investigate noise, search for the player, use cover, and engage when they spot you. Movement, aiming, crouching, and damage affect combat.

## Settings and performance

- **Graphics:** Low, Medium, and High presets adjust forest density, shadows, effects, and render resolution.
- **Look sensitivity:** Adjust mouse/touch look speed.
- **Custom controls:** Touch layouts can be saved locally per browser.

For smoother performance on older devices, choose **Low** graphics and close other GPU-intensive tabs.

## Technical notes

- The project is intentionally kept as a single-page app; game logic and styling live in `index.html`.
- Three.js is loaded from cdnjs (r128).
- Audio is generated with the Web Audio API after the first user interaction.
- No server, account, or backend is required.

## Development

There is no compile or automated test command at present. For local development, serve the repository directory with any static HTTP server and open `index.html`. This is useful for testing browser behavior and avoiding local-file restrictions.

## License

No license file is currently included. Unless the repository owner adds a license, all rights remain with the copyright holder; do not assume the code is available for reuse or redistribution.
