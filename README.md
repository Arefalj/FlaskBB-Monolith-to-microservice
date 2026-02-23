🚀 FlaskBB-Architect: Microservice Extraction via GNN & LLM
FlaskBB-Architect is an automated framework designed to solve the complexity of decomposing monolithic systems into microservices. Developed as a final project at Iran University of Science and Technology (IUST), this tool moves beyond simple static analysis by combining Large Language Models (LLMs) for semantic context and Graph Neural Networks (GNNs) for structural dependencies.

🎓 Academic Impact
This project implements a novel method for architecture reconstruction. When tested on the FlaskBB open-source project, the methodology achieved:

+100% Improvement in Cohesion metrics.

50% Reduction in Coupling metrics.

Optimized Separation verified by Silhouette scores.

🛠️ Core Features
🔍 Deep Static Analysis
AST Extraction: Advanced parsing of Python source code into Abstract Syntax Trees to identify File, Class, Function, and Module entities.

Relationship Mapping: Comprehensive detection of:

Contains: Structural hierarchy.

Imports: Module-level dependencies.

Calls: Functional call-graph interactions.

🧠 Intelligent Decomposition
Semantic Understanding: Integrates OpenAI embeddings to understand the purpose of code, not just its syntax.

Structural GNN: Processes the code graph to ensure clusters respect software engineering principles.

📊 Visualization
Interactive Graphs: Generates dynamic HTML visualizations using PyVis.

Cluster Legends: Clear, color-coded identification of proposed microservice boundaries.

📂 Repository Structure
🚀 Getting Started
1. Installation
2. Configuration
Ensure you have your OpenAI API key set in your environment variables for semantic analysis:

3. Usage
Run the main analysis script to generate the interactive architecture graph:

The output will be saved as code_graph.html and graph_clustered.html.

✍️ Author
Aref Alijannejad Bachelor of Science in Computer Engineering Supervisor: Dr. Mehrdad Ashtiani

University: Iran University of Science and Technology (IUST)

Date: February 2026
