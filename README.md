
# MYLO 
MYLO is a Machine Learning platform built as an intelligent engine for creating, analyzing, and optimizing models, where neural network architectures become fully programmable. Instead of treating models as "black boxes," MYLO transforms them into editable dynamic graphs, enabling real-time structural modifications, automatic validation, and secure execution.

The system combines an advanced architecture editor, data analysis, and state-of-the-art optimization algorithms (neuroevolution and Optuna Hyperparameter Optimization), providing both fine-grained control for experts and aggressive automation for rapid results. In practice, MYLO doesn't just train models—it understands them, reconstructs them, and evolves them.

![Hero image](http://data.infoeducatie.ro/uploads/screenshot/screenshot/3671/Final_Start.png)

# Try it out here: https://mylo-web-deployument.vercel.app/

## Setting up the client
Read more about it here: https://mylo-web-deployument.vercel.app/docs#local-agents

### For a demo project visit the catalog page in the dashboard and choose the available Demo project
![Catalog page showing the app demo project](https://i.imgur.com/sTXtCBM.png)


# Executive Summary

  

MYLO (Visual Neural Network Studio) is a web-based platform that enables users — from students to ML practitioners — to visualize, edit, analyze, and optimize neural networks in an integrated environment without manually writing PyTorch code.

The project combines three main components:
| Component | Role |
|---|---|
| **Web Interface (Next.js)** | User interface: authentication, dockable dashboard, visual editor, AI assistant |
| **Desktop Agent (FastAPI + PyTorch)** | ML engine: data processing, descriptor editing, neuroevolution, model export |
| **Orchestrator (FastAPI + Docker)** | Dynamic provisioning of CLOUD agents in isolated containers |

  

The user works in an IDE-like workspace with detachable panels for the file explorer, model editor, CSV analysis, optimization, diagnostics, and AI chat. All operations are executed by an agent — either locally (on the user's machine) or in the cloud (inside a Docker container launched on demand).

  

## Key Innovations Compared to a Simple ONNX Viewer

  

-  **ArchitectureDescriptor** — represents the model architecture as an editable graph rather than just a static visualization.
-  **Model Editor** — enables adding and removing layers, modifying activations, and creating skip connections, with automatic shape propagation.
-  **Neuroevolution** — automatically optimizes the architecture using the user's data.
-  **Weight Transfer** — accelerates training after architectural mutations by transferring compatible weights.
-  **AI Assistant** — enables model editing through natural language, using agent-side tools.
-  **CLOUD Mode** — provides an isolated agent for each session, with no local installation required.

# Documentation [RO]
[Documentation](https://docs.google.com/document/d/1bOaJbjaP7HBHJHmbMLrH6HiqskNWnJEbzksapTdhZ0U/edit?usp=sharing)
^^ worth a read if you translate it for more tehnical depth

## Authors
[Telea Mihai](https://github.com/Telea-Mihai) - Web Interface and Integration with the Agents
[Benedek Robert](https://github.com/Robi2903) - Descriptor system, Optimization Algorithm, Model and Data Processing Tools
