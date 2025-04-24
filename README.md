# 🧠 Codebase Analyzer & Dependency Visualizer

This project provides tools to analyze a Python codebase, extract static and dynamic dependencies, and visualize them as a block diagram. It uses static AST parsing and optionally leverages Together.ai's LLM for dynamic import detection.

## 🔧 Features

- Extracts static imports and exports from Python files
- Optionally detects dynamic dependencies using LLM
- Constructs and visualizes dependency graphs using `networkx` and `pygraphviz`
- Generates JSON and markdown reports of code relationships

## 📦 Requirements

- Python 3.7+
- `networkx`, `matplotlib`, `pygraphviz`, `together`

Install required packages:

```bash
pip install networkx matplotlib pygraphviz together
