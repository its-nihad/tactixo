# TactiXO

TactiXO is a two-player tic-tac-toe game built as a single self-contained HTML file, with no external libraries or dependencies. Everything needed to run it, including the layout, styling, and game logic, lives in one file, so it works offline and can be dropped straight into GitHub Pages or opened directly in a browser.

The design leans into a dark, ink-toned interface with two distinct accent colors, a warm coral for Player X and a cool cyan for Player O, carried through the wordmark, the marks on the board, and the scoreboard. Marks are drawn with a short animated stroke rather than appearing instantly, and a winning line is swept across the board in gold when a round is won.

The game tracks wins for each player along with draws across a full scoreboard, and highlights whose turn it currently is. A "New round" button clears the board while keeping the running score, and a "Reset scores" button starts everything over from zero. The board is fully keyboard accessible, with visible focus states on every cell and control, and the layout adapts down to small mobile screens.

To play, just open the file in any modern browser. No build step, server, or installation is required.
