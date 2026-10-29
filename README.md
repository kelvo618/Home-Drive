# Home & Drive Simulator

A browser-based 3D simulator: walk around a house, step out the front door, enter the garage and drive one of four cars.

**Play:** enable GitHub Pages for this repo (Settings → Pages → Deploy from branch → `main` / root) and open the link.

## Features
- Walkable house (living area, kitchen, bedroom, garage) with collisions and an auto-opening front door
- Procedural human with walk/run gait: swinging arms, bending knees, torso twist, body bob, footstep sounds
- Four cars (sedan, SUV, sports coupe, hatchback) with clear-coat paint, reflections, steering wheels, body roll and pitch, brake lights
- Driving physics with speed-sensitive steering, handbrake, reverse and collisions; engine sound with gear shifts
- Sky, sun, reflections (environment map), real-time shadows and procedural textures

## Controls
| Action | Keyboard | Touch |
|---|---|---|
| Move / drive | WASD or arrows | Left-side joystick |
| Run | Shift | Push joystick fully |
| Look | Drag mouse | Drag right side |
| Enter / exit car | E | E button |
| Handbrake | Space | Brake button |
| Zoom | Mouse wheel | – |

## Run locally
Open `index.html` in a browser (needs internet for the three.js CDN), or serve the folder with `python3 -m http.server`.

## Tech
Single file, [three.js](https://threejs.org) r128, no build step. License: MIT.
