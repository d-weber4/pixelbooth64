# PixelBooth 64 🎃

A retro-style photobooth web app (PWA) — currently in its **Halloween party** edition.

**Modes:** single photo, 4-photo filmstrip collage, video message (up to 1 min), and a draw-on guestbook. Photos can be decorated with stickers, frames and text, saved via Firebase with a QR code guests scan to download their shot. Captures from the last 24 hours appear in the session gallery.

**Halloween edition:** spooky theme (pumpkin orange / haunted purple / slime green), a SPOOKY sticker pack, pumpkin / haunted / spider-web frames, SLIME and MIDNIGHT filters, and a Creepster title font.

**Performance overhaul (Oct 2026):** JPEG capture pipeline (no more multi-MB PNG strings), a cached photo+frame layer with requestAnimationFrame redraws in the editor, unified Pointer Events with pinch-to-resize/rotate and full-size touch handles, normalized sticker coordinates so rotating the device never scrambles a layout, and a camera stream that stays warm between shots for instant retakes.

Just static files — serve the folder over HTTPS (camera access requires it) and open `index.html`.
