The Daily Mini Crossword

A fully playable, customizable recreation of the Mini Crossword, built with HTML, CSS, and JavaScript.

Online
  (https://iankelley05.github.io/Daily_Mini/)

Locally
  Clone this repository or download the index.html file.
  Open index.html in any web browser.
  Start solving!

Features

  Authentic Feel: Keyboard navigation behaves just like the real app (arrow keys to move, space bar to toggle direction).
  Smart Navigation: The cursor automatically skips over filled squares and jumps to the next word.

Helper Tools:

  Check: Verify a square, word, or the entire grid (incorrect letters turn red).
  Reveal: Give up? Reveal a square or word (revealed letters turn green).
  Timer: Tracks how fast you can solve today's puzzle.
  Mobile Friendly: Works perfectly on phones with touch-optimized grids.

How to Customize the Puzzle

You can change the words and clues daily by editing the PUZZLE_DATA object inside index.html.

Open index.html in a text editor (VS Code, Notepad, etc.).

Scroll down to the <script> section (approx. line 320).

Update the Grid:

grid: [
    ['H', 'E', 'L', 'L', 'O'],
    ['.', 'A', 'P', 'P', 'L'], // Use '.' for black squares
    // ...
]


Update the Clues:

clues: {
    across: [
        { num: 1, text: "A standard greeting" },
        // ...
    ],
    down: [
        // ...
    ]
}


Save the file and push your changes to GitHub to update the live site!

Deployment
  
  This project is designed to be hosted for free on GitHub Pages.
  Push index.html to a public GitHub repository.
  Go to Settings > Pages.
  Select the main branch and click Save.
  Your game will be live in a few minutes!
