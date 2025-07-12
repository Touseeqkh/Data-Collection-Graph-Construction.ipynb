# Gabriela Mistral Wikipedia Network Visualization

This repository contains a Google Colab notebook that builds an interactive directed graph to explore the Wikipedia network of the Chilean poet and diplomat **Gabriela Mistral**.

---

## Overview

The notebook fetches Gabriela Mistral's Wikipedia page and extracts all outgoing links. It identifies mutual references by checking if linked pages also link back to Gabriela Mistral.

The graph shows:

- Outgoing links (edges from Gabriela Mistral to other pages)
- Incoming links (edges from other pages back to Gabriela Mistral)
- Node sizes scaled by PageRank scores to highlight influential nodes

---

## How to Use

1. Upload the notebook `Gabriela_Mistral_Wikipedia_Network.ipynb` to your Google Drive or open it directly in [Google Colab](https://colab.research.google.com/).
2. Run all cells.
3. Modify the `person` variable in the first cell to explore other Wikipedia pages.

---

## Dependencies

The notebook requires these Python libraries:

- `wikipedia-api`
- `networkx`
- `matplotlib`

You can install them with:

```bash
pip install wikipedia-api networkx matplotlib
