# Debug Detective

Debug Detective is a bilingual browser game for learning Python debugging through an interactive detective case board. It is built as a single self-contained HTML file with HTML, CSS, and JavaScript, so it runs without a build step or external backend.

## What is inside

- 11 playable case files: 1 guided tutorial plus 10 progressively harder cases
- English and Bangla interface toggle
- Three-step investigations: run the evidence, identify the suspect line, and submit a fix
- Adaptive hints that reveal stronger clues after repeated wrong attempts
- Rank-based performance scoring: Rookie, Skilled, and Master
- XP rewards, streak tracking, attempt counters, and per-case hint tracking
- Persistent progress in browser `localStorage`
- Cold Case archive for reviewing solved cases
- Teacher Summary with case-by-case results and a print-friendly report
- Hard Mode unlocked after all 11 cases, with a 90-second timer per replay and 2x XP
- Keyboard shortcuts and reduced-motion support

## Learning topics

The cases use short Python snippets to teach common debugging patterns:

- Syntax errors: missing colons and unmatched quotes
- Arithmetic and comparison operators
- Boundary and conditional logic errors
- Python `range()` off-by-one behavior
- Accumulator initialization
- Variable-name mistakes
- Multi-bug tracing and modulus-based even-number checks

The game is designed around the NCTB Class 9-10 ICT curriculum context, especially introductory programming and debugging practice. It is an educational practice tool, not an official NCTB publication.

## Run locally

No installation is required. Open `index.html` in a modern browser, or serve the folder with any static file server:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages

Because the project is static, it can be published with GitHub Pages by selecting the repository's `main` branch and root folder as the Pages source.

## Project structure

```text
index.html   # Complete game: markup, styles, data, and behavior
README.md    # Project documentation
```

## Credits

Designed by Md. Raiyan Ibne Kamal.
