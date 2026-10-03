# Rainbow Fox

A peaceful third-person journey between a black forest made of rainbow light and an interstellar sea of stars. Guide a luminous fox between speckled trees, leave a fading trail, and discover drifting lights. Run and leap when you want a little exhilaration. There is no score, timer, or danger.

## Play

Clone or download this repository, then **double-click `RainbowFox.html`**. It opens directly in your browser. If your computer opens HTML files in an editor, use **Open with → Chrome, Edge, Firefox, or Safari**.

No terminal, installation, server, internet connection, or account is required. Everything—including the procedural forest, fox, and optional synthesized sound—is inside the HTML file. Use a current desktop browser for the best experience; touch controls also appear on touch devices.

- **W / ↑:** move forward
- **S / ↓:** step back
- **A / ←, D / →:** turn
- **Right mouse + drag:** orbit the camera horizontally and vertically
- **Mouse wheel:** zoom in or out
- **Shift:** run
- **Space:** leap
- **Escape:** pause or resume
- **Sound:** toggle the ambient drone, wind, and light chimes (off initially)

The forest wraps endlessly. Floating light clusters respond when you approach. Hold the right mouse button and drag to orbit independently of the fox: W / S continue along her heading, and A / D turn her body. You can hold W + Shift and orbit to her profile to watch her gallop from the side. When she is still, A / D make her lift and reposition her paws as she turns, keeping supporting paws planted and shifting her weight between steps. She finishes setting down her paws when you release the turn key.

An idle camera keeps its angle; after you release right mouse, walking eases it back behind her. Vertical orbit and zoom are limited to keep her in view. Releasing the mouse button, opening the guide, pausing, or switching windows ends camera drag. Switching away pauses the experience.

## Between trees and stars

Follow the line of low, drifting lights ahead of the starting point to **the stillwater**, a reflecting pool in an open clearing. The quiet direction hint at the bottom helps you find it if you wander off.

Walk onto the pool and continue across it. Your footsteps make little spiral ripples, the trees dissolve upward, and the sky opens around a ribbon of stardust. You can stop, linger, or turn back before the crossing completes. The camera gently widens and, with sound enabled, wind gives way to a softer celestial chord.

In space, the same movement, galloping, jumping, and independent camera controls work. Follow the gently winding stardust ribbon past nebulae and a distant ringed planet. The path has forgiving edges, so there is no falling; a later fork offers another route.

A glowing **tree constellation** stands beside the first stretch of path, marked “A way home.” Approach its base to return. Over a few seconds the constellation becomes the same clearing, with the pool beneath you and familiar trees around you. Your position and controls remain continuous. Step away from the clearing before crossing the pool again; you can make the journey as many times as you like.

## Development

Edit `RainbowFox.html`, save, and refresh the browser. It uses the built-in Canvas 2D and Web Audio APIs with no external dependencies or build step. The trees and fox are projected three-dimensional particle forms, rendered on a black canvas. Audio starts only after pressing Sound.

The fox has a tapered muzzle, triangular ears, a narrow waist, a white chest and tail tip, and dark stockings. Articulated legs use grounded stance and lifted swing phases, blending a four-beat walk into a gallop. Her spine, head, and brush tail respond to movement and turns; jumping tucks her legs and landing briefly compresses her posture.
