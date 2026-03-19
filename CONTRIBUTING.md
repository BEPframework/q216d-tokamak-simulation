# Contributing to Q216D Tokamak Simulation

Thanks for your interest in contributing! Q216D is a single-file browser-based 3D tokamak simulator with TASD attractor control.

## Ways to Contribute

- **Bug reports** — open an issue describing the problem, your browser/OS, and steps to reproduce.
- **Feature requests** — open an issue with a clear description of the proposed feature and its relevance to tokamak simulation or TASD control.
- **Code contributions** — fork the repo, make your changes, and submit a pull request.
- **Physics feedback** — if you spot plasma modeling issues or have suggestions for improving TASD energy transition control, open an issue or discussion.

## Guidelines

1. **Single-file architecture** — the simulation lives in one self-contained HTML file. Three.js and Pyodide are loaded from CDN. Please keep it self-contained.
2. **Keep it accessible** — the tool is designed for researchers, students, and anyone curious about tokamak physics. Clear UI labels and readable code comments matter.
3. **Test before submitting** — open the file in at least two browsers (Chrome + Firefox recommended) and verify your changes don't break the 3D visualization, energy transitions, charts, or event simulation.
4. **Respect the model** — this is a TASD-enhanced simulation platform. Keep that framing in any documentation or UI text.

## Code Style

- Vanilla JS + Three.js, no additional frameworks.
- Use `const` / `let`, never `var`.
- Descriptive variable names; comments for non-obvious physics logic.

## Pull Request Process

1. Fork and create a feature branch (`git checkout -b feature/my-feature`).
2. Make your changes in `index.html`.
3. Test thoroughly (3D rendering, controls, charts, pellet/MGI events, sound).
4. Submit a PR with a clear description of what changed and why.

## License

By contributing, you agree that your contributions will be licensed under the Apache License, Version 2.0.

## Contact

For questions, reach out to **Nicolas B. Quiroz, MD** via [GitHub](https://github.com/BEPframework).
