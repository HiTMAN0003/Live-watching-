# Live Duo

A responsive, static page for viewing two YouTube live streams and their embedded live chats side by side.

## GitHub Pages deployment

1. Upload `index.html`, `README.md`, and `.nojekyll` to the root of the `main` branch.
2. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
3. Open `https://hitman0003.github.io/youtube-live/` after the Pages deployment finishes.

## Important limitations

- YouTube must permit embedding for the selected video. Some live streams cannot be embedded.
- Live chat embedding may be disabled by the channel or unavailable for some streams.
- This static page does not sign in to YouTube and does not use the YouTube Data API.
- Open the website over HTTPS, not as a local `file://` page.
- GitHub Pages is static hosting. No API secrets or OAuth client secrets should be placed in this repository.
