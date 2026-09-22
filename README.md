# Debug Detective

> A bilingual detective-style debugging game built and designed by **Md. Raiyan Ibne Kamal**.

[Play on GitHub Pages](https://raiyanibnekamal.github.io/Debug-Detective/) · [View the source](https://github.com/raiyanibnekamal/Debug-Detective)

Debug Detective is a bilingual browser game for learning Python debugging through an interactive detective case board. It is built as a single self-contained HTML file with HTML, CSS, and JavaScript, so it runs without a build step or external backend.

## Project identity

- **Author:** [Md. Raiyan Ibne Kamal](https://github.com/raiyanibnekamal)
- **Project type:** Educational browser game / portfolio project
- **Languages used:** HTML, CSS, JavaScript, English, and Bangla
- **Game content:** Python debugging examples aligned with the Class 9-10 ICT learning context
- **Architecture:** Single-page, client-side application with no server or database
- **License:** MIT

The game concept, interface, case data, scoring system, bilingual content, and implementation are authored by Md. Raiyan Ibne Kamal. NCTB is referenced as curriculum context only; this is not an official NCTB publication.

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

## Design and implementation

The interface uses a noir detective evidence-board theme to turn debugging into an investigation workflow. Each case guides the learner from observing program output, to locating the faulty line, to selecting or entering a correction. Progress, ranks, XP, hints, and solved cases are stored locally in the learner's browser, so no account or personal data is required.

The project intentionally has no build pipeline or dependency installation. Google Fonts are loaded at runtime for the visual style; the game logic and content remain in `index.html`.

## Run locally

No installation is required. Open `index.html` in a modern browser, or serve the folder with any static file server:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages

The live version is published from the `main` branch:

https://raiyanibnekamal.github.io/Debug-Detective/

## Project structure

```text
index.html   # Complete game: markup, styles, data, and behavior
README.md    # Project documentation
```

## Credits

Built and designed by **Md. Raiyan Ibne Kamal**.

## License

This project is available under the [MIT License](LICENSE).
