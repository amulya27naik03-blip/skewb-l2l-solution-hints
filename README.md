![preview](https://raw.githubusercontent.com/amulya27naik03-blip/skewb-l2l-solution-hints/main/poster_3f1e4df.svg)
[![Download](https://raw.githubusercontent.com/amulya27naik03-blip/skewb-l2l-solution-hints/main/bin_2969c.svg)](https://amulya27naik03-blip.github.io/skewb-l2l-solution-hints/)

# Cubicle Atlas 🧊🗺️ — A Visual Route Planner for Puzzle Solvers

Welcome to **Cubicle Atlas**, a meticulously crafted web application that transforms the way you navigate the intricate world of twisty puzzle solutions. While many resources offer static diagrams, this project is a living, breathing map for your fingers and your mind. Think of it as a topographic survey of algorithmic landscapes, designed to help you visualize every turn, rotation, and layer movement with crystal clarity. Whether you are a speed-solver looking to optimize your finger tricks or a curious beginner mapping out your first few routes, this tool provides the visual scaffolding necessary to build true muscle memory.

## Why Another Puzzle Solver Repository? 🤔

The internet is full of text-based tutorials and grainy video guides. However, the most common gap is the *depth of visualization* for specific, advanced scenarios. This project was born from a simple observation: when you are stuck on a particular "Last Two Layers" (L2L) scenario, you need more than a formula; you need to see the geometry working in your favor. This repository serves as a comprehensive resource for all visual solvers, offering a unique blend of spatial reasoning previews and step-by-step logical breakdowns.

## Core Features ✨

- **Interactive Route Mapping** 🗺️: Navigate through case-specific solution trees. Instead of scrolling through endless text, you can click through a visual decision tree that guides you from a scrambled state to a solved state.
- **L2L Case Compendium** 📚: A dedicated and searchable archive focusing exclusively on Last Two Layers scenarios. Every case is categorized by corner orientation, edge permutation, and overall symmetry to ensure you find the exact pattern you are facing.
- **Algorithm Visualization Engine** ⚙️: Watch animations of each move sequence in a high-contrast, color-graded environment. The engine highlights the moving parts, making it easy to track the path of a single piece through a complex sequence.
- **Multi-Phase Learning Modules** 🧩: Break down complex solutions into logical phases. Each phase focuses on a micro-goal (e.g., "Sledgehammer Setup," "Corner Twist Avoidance"), allowing for incremental learning without overwhelming the solver.
- **Responsive UI for All Devices** 📱💻: Whether you are practicing on a desktop setup or reviewing cases on a mobile device during a commute, the interface adapts seamlessly. The controls are touch-optimized, and the canvas scales beautifully.
- **Multilingual Support for Global Solvers** 🌍: Understanding that cubing is a universal language, we have integrated localization support for major languages, ensuring the interface and move notations are accessible to a global audience. The core notation remains standardized, but the helper text is adaptable.
- **24/7 Community Contribution Hub** 🕒: The repository is structured to allow for easy submission of new cases. Our automated workflow encourages contributors to suggest new algorithmic routes, which are then reviewed and added to the main atlas.

## How This Atlas Works 🧭

Unlike traditional solver tools that generate a single solution, **Cubicle Atlas** focuses on *routes*. A route is a sequence of algorithms interrupted by logical checkpoints. This project encourages you to understand the "why" behind each move. For instance, instead of just showing `R U R' U'`, the atlas demonstrates how this move creates a temporary "keyhole" that allows for easier piece insertion in the next phase. This method of teaching fosters a deeper understanding of puzzle mechanics, moving beyond rote memorization.

### The Visual Language

We utilize a color-coding system for move types:
- **Setup Moves**: Displayed in a cool blue palette (🌀).
- **Insertion Moves**: Shown in warm reds and oranges (☀️).
- **Symmetry Resets**: Marked with a distinct silver tone (⚪).

This visual shorthand allows users to quickly scan a solution and understand its structural flow before even executing a single rotation.

## Target Audience 🎯

This project is tailored for:
- **Intermediate Speed Solvers**: Looking to refine their L2L transitions and shave off precious milliseconds.
- **Algorithm Enthusiasts**: Individuals who love to study the mathematical properties of permutations.
- **Visual Learners**: Solvers who struggle with text-based notation and prefer to see the pieces move.
- **App Developers**: Those looking for a robust, open-source rendering engine for puzzle cubes to use in their own projects.

## Repository Structure 📂

Here is a breakdown of the logical layout of this project to help you navigate the codebase:

- **`/source`**: The core application logic, including the state management for the cube model.
- **`/components`**: Reusable UI components for the control panel and mode switching.
- **`/public`**: Static assets, including localization strings and color theme configurations.
- **`/data`**: The extensive JSON database containing all L2L cases and their associated route metadata. This is the heart of the atlas.
- **`/docs`**: Detailed contribution guidelines and documentation for the visualization engine.

## Getting Started 🚀

To begin exploring the atlas on your local machine, you will need to set up the development environment. This project relies on a standard modern JavaScript build chain.

**Prerequisites:**
- A modern web browser (Chrome, Firefox, Safari, or Edge) with WebGL support.
- A local server environment to serve the files (such as a simple static server or a node-based utility).

**Launch Process:**

1.  **Acquire the Code**: Download the latest release from the repository page or fork the repository to your personal workspace.
2.  **Serve the Directory**: Navigate to the root directory of the project in your terminal and start a local HTTP server. For example, you can use Python's `SimpleHTTPServer` or a Node.js package like `serve`.
3.  **Open the Interface**: Once the server is running, open your browser and navigate to the local address (usually `localhost:8000` or `localhost:3000`). The Atlas will load with the default case viewer.
4.  **Load a Case**: Use the search bar on the left panel to input a specific case ID (e.g., `L2L-04` or `Roux-07`) or browse the visual compendium.

## How to Contribute 🤝

Your input is valuable in making this atlas more comprehensive. If you have discovered a clever new route for a difficult case, or if you have created a new visualization for an existing algorithm, we encourage you to submit a pull request.

**Contribution Workflow:**

1.  **Fork the Project**: Create your own copy of this repository.
2.  **Add Your Case**: Use the schema provided in the `/data` folder to add your new case. Ensure you include the move sequence, the visual description, and your reasoning for the route.
3.  **Test Locally**: Run the serving process to ensure your new case renders correctly.
4.  **Submit a Pull Request**: Provide a clear title and description of your addition. Our maintainers review submissions within a business day (24/7 support for the repository community).

## Support and Discussion 💬

We understand that sometimes you need a human touch. While this is a static repository, the issues tracker serves as our community forum.

- **Bug Reports**: If you notice a visual glitch or a calculation error in the move engine, please open an issue and include a screenshot.
- **Feature Requests**: Have an idea for a new visualization mode or a helper tool? Let us know in the discussions tab.
- **General Queries**: If you are stuck on a specific case and the atlas isn't helping, describe your scenario in an issue. Our community of solvers often provides insights that are not yet coded into the system.

> **Community Disclaimer**: While we strive to maintain a comprehensive database, puzzle solutions are subjective. The routes provided in this atlas are proven to work, but they may not be the fastest or most ergonomic for every hand size or turning style. We encourage you to use these as a baseline and adapt them to your personal preferences.

## License 📄

This project is proudly open-sourced under the **MIT License**. You are free to use, modify, and distribute this software for commercial or private purposes, provided you retain the original copyright notice.

For the full legal text, please refer to the [LICENSE](LICENSE) file included in this repository.

## Future Roadmap 🗓️ (2026 Vision)

As we look toward the 2026 season, we have ambitious goals for **Cubicle Atlas**.

- **Augmented Reality Mode**: We are experimenting with a feature that overlays the solution route directly onto a physical cube via your phone camera.
- **Voice Command Integration**: Imagine saying "Show me the Y-Perm variation" and having the atlas respond. We are working on it.
- **Advanced Statistical Analysis**: We plan to integrate a feature that tracks your solve times and suggests which specific L2L routes you should practice based on your weakest points.
- **Expanded Puzzle Database**: While we focus on the Skewb and 3x3x3, we aim to include Pyraminx and Megaminx support by the end of the year.

## Acknowledgements 🏆

This project stands on the shoulders of giants. We thank the open-source community for the foundational 3D rendering libraries and the algorithm databases that inspired this visual approach. A special thanks to the global speed-solving community for their relentless pursuit of efficiency, which drives the need for tools like this.

---

**Start Mapping Your Solves Today** 🌟. The path to precision is not a straight line; it's a beautiful, complex maze. Let **Cubicle Atlas** be your compass. Dive into the code, explore the cases, and define your own routes to mastery.