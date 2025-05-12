# Multi-Dimensional Capitalism

Multi-Dimensional Capitalism (MDC) is a conceptual framework and modeling toolkit designed to analyze, simulate, and optimize systems of value creation and exchange across multiple forms of capital—beyond purely financial metrics. MDC enables researchers, policymakers, and organizational leaders to map interactions between diverse capital types such as economic, social, cultural, intellectual, moral, narrative, computational, and temporal capital, and to evaluate system coherence, degenerative currents, and transformation pathways.

## Table of Contents

* [Key Concepts](#key-concepts)
* [Project Structure](#project-structure)
* [Getting Started](#getting-started)
* [Usage](#usage)
* [Core Components](#core-components)
* [Case Studies & Examples](#case-studies--examples)
* [Visualization & Diagrams](#visualization--diagrams)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)

## Key Concepts

* **Multidimensional Capital:** Extends traditional financial capital to include social, cultural, intellectual, moral, narrative, computational, and temporal dimensions.
* **Cultural Combinators:** Entities (individuals, institutions, artifacts) that transform one form of capital into another.
* **Capital Currents:** Flows of capital through systems, including emergent and degenerative currents.
* **System Coherence:** Measure of net positive value creation across capitals; contrasted with decoherent structures that extract more value than they create.

## Project Structure

The repository is organized as follows:

```
Multidimensional-Capitalism/
├── multidimensionalcapitalism.md      # Primary source (frequently updated Markdown)
├── multidimensionalcapitalism.pdf     # Generated LaTeX PDF (not the latest version)
├── fileformat.md                     # Definitions of JSON graph file structures
├── Interactive/                       # Web-based interactive models
│   ├── index.html                    # Entry point for the interactive visualizer
│   ├── app.js                        # Core JavaScript application logic
│   └── Graphs/                       # Sample model files (JSON configurations)
│       ├── example-system-1.json
│       └── example-system-2.json
```

> **Note:** The authoritative content lives in `multidimensionalcapitalism.md`. The PDF is generated periodically but may lag behind the Markdown updates.

## Getting Started

1. **Preview the Markdown**: Read `multidimensionalcapitalism.md` for the latest framework descriptions.
2. **Interactive Visualizer**:

   * Open `Interactive/index.html` in your browser to explore sample models.
   * Modify or add JSON configurations in `Interactive/Graphs/` to test new scenarios.
3. **Local Development** (optional):

   ```bash
   git clone https://github.com/your-org/multi-dimensional-capitalism.git
   cd multi-dimensional-capitalism
   ```

## Usage

* **Editing the Framework**: Update `multidimensionalcapitalism.md` with new capital types, combinators, or currents.
* **Defining Systems**: Use `fileformat.md` as a reference to create or modify JSON model files in `Interactive/Graphs/`.
* **Simulations & Analysis**: (If code lives in `src/`) Run Python or other scripts to simulate capital flows and compute coherence metrics.

## Core Components

See `multidimensionalcapitalism.md` for detailed explanations of:

* Capital Types
* Cultural Combinators
* Capital Currents (Emergent & Degenerative)
* Coherence vs. Decoherence

## Case Studies & Examples 
* TBD


## Visualization & Diagrams

* Interactive visualizer: `Interactive/index.html`
* Static exports: `diagrams/` contains PNG/SVG maps

## Contributing

1. Fork the repo.
2. Create a feature branch.
3. Update `multidimensionalcapitalism.md` or add new JSON models under `Interactive/Graphs/`.
4. Verify changes: refresh `Interactive/index.html` for new graph files.
5. Submit a pull request with clear descriptions.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact

For questions or collaboration inquiries, please open an issue or email the maintainers at `maintainers@mdc.org`.
