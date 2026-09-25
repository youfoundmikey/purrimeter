# Arkade

Nine games, one arcade. No build step: plain static HTML that Vercel serves as-is.

| Game | Folder | What it is |
|---|---|---|
| Purrimeter | `/purrimeter` | One cat per row, column and color zone. Cats can't touch. |
| Fillmore | `/fillmore` | Drag one line through every block of a carved-up board. |
| Block Party | `/blockparty` | 8×8 block puzzle. Clear lines, don't get boxed in. |
| Face Off | `/faceoff` | Guess who against an Easy or Hard bot. |
| Darts | `/darts` | 301 against a bot. Two timing sweeps aim each dart. |
| Domino | `/domino` | Draw dominoes against a bot, first to 50. |
| Ludo | `/ludo` | Race 1 or 3 bots home. Captures, safe stars, extra rolls. |
| Minesweeper | `/minesweeper` | Three sizes, safe first tap, long-press to flag. |
| Pool | `/pool` | 8-ball against an Easy or Hard bot, or two players on one phone. |

The home page (`index.html`) links to each game, and each game has a back button to the arcade.
Progress, best scores and records are saved in the browser.

On a phone, open it in Safari (or Chrome), tap Share → Add to Home Screen, and it launches full-screen like a native app.
