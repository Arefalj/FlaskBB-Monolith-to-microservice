# FlaskBB Architecture Analyzer

A tool for automated static code analysis and architectural visualization of the [FlaskBB](https://github.com/flaskbb/flaskbb) project. This tool parses Python source code into Abstract Syntax Trees (AST) to map dependencies and relationships between different code entities.

## 🚀 Features
- **Project Scanner**: Automatically identifies and filters Python source files while ignoring tests and migrations.
- **AST Node Extraction**: Identifies four key entity types: `file`, `class`, `function`, and `module`.
- **Relationship Mapping**: Detects structural links including:
  - `contains`: Which classes/functions belong to which files.
  - `import`: Module-level dependencies.
  - `call`: Functional call-graph mapping.
- **Interactive Visualization**: Generates a dynamic HTML graph using `PyVis` to explore the codebase visually.

## 🛠️ Installation
1. Clone the repository.
2. Install the necessary analysis tools:
   ```bash
   pip install -r requirements.txt