# PhotoQR

Turn a photo into a QR code that still scans. Pick a picture, paste a link, tune the look, download the PNG.

Everything runs in your browser. The picture never leaves your device. No account, no watermark, no backend.

**Live:** https://meetaxel.github.io/photoqr/

## Features

- Photo-tinted QR with high error correction (level H)
- Sliders for photo strength, contrast, dot size and margin
- Clean card or stamp frame, square or round dots
- A built-in check warns when a setting may not scan reliably
- Download as PNG

Always scan the result with your phone before you use it. Very long links make dense QR codes that may not scan.

## Credits

QR encoding uses [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) by Kazuhiko Arase, MIT license. Idea inspired by a reel by aleksandra.desssign.

The site is a single `index.html`, so it also works when opened from a file.
