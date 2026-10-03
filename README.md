# Rainbow Fox

A peaceful third-person journey through a black forest made of rainbow light. Guide a luminous fox between speckled trees, leave a fading trail, and discover drifting lights. Run and leap when you want a little exhilaration. There is no score, timer, or danger.

## Play

Clone or download this repository, then **double-click `RainbowFox.html`**. It opens directly in your browser. If your computer opens HTML files in an editor, use **Open with → Chrome, Edge, Firefox, or Safari**.

No terminal, installation, server, internet connection, or account is required. Everything—including the procedural forest, fox, and optional synthesized sound—is inside the HTML file. Use a current desktop browser for the best experience; touch controls also appear on touch devices.

- **W / ↑:** move forward
- **S / ↓:** step back
- **A / ←, D / →:** turn
- **Shift:** run
- **Space:** leap
- **Escape:** pause or resume
- **Sound:** toggle the ambient drone, wind, and light chimes (off initially)

The forest wraps endlessly. Floating light clusters respond when you approach. The camera follows behind the fox; turning changes her direction and the camera eases after her. Switching away pauses the experience.

## Development

Edit `RainbowFox.html`, save, and refresh the browser. It uses the built-in Canvas 2D and Web Audio APIs with no external dependencies or build step. The trees and fox are projected three-dimensional particle forms, rendered on a black canvas. Audio starts only after pressing Sound.
