<p align="center"><img src="logo.svg" width="96" alt="AI Othello logo"></p>

# AI Othello

A two-player Othello (Reversi) game in a single HTML file. Each player picks an
AI as their side — OpenAI, Grok, Copilot, Meta, Gemini or Claude — and the discs
carry that AI's token.

## Play

Open `index.html` in any browser. There is nothing to install or build.

To put it online, turn on GitHub Pages for this repository (Settings → Pages →
deploy from the `main` branch, root folder). The game will be served at
`https://<your-username>.github.io/<repo-name>/`.

## How it works

- Two people share one screen and take turns.
- Yellow dots mark the squares where the current player can move.
- A move must trap at least one of the other side's discs in a straight line;
  trapped discs flip to your side.
- If a player has no move, the turn passes back. The game ends when neither
  player can move, and the side with more discs wins.

## Tokens and logos

The built-in tokens are plain symbols, not the companies' logos. To play with a
real logo, choose "Use my own image" under either player and pick an image file
from your device. The image stays in your browser and is not saved or uploaded.

All product and company names are trademarks of their respective owners. This
project is not affiliated with or endorsed by any of them.

## Files

- `index.html` — the whole game: markup, styles and script
- `logo.svg` — repository logo and page icon
- `LICENSE` — MIT licence

## License

MIT. See `LICENSE`.
