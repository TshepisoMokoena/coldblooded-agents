# 🛠️ Welcome to Workflows Tutorials

This repository contains **easy-to-follow Jupyter notebooks** focused on building, customizing, and running **Workflows** using the LlamaIndex library.

---

## 🚀 What are Workflows?

In LlamaIndex, **Workflows** allow you to structure complex AI tasks into **modular steps** connected by **events**.  
Instead of writing one large function, Workflows break down logic into **independent, manageable units** that can run **asynchronously**, **concurrently**, and **flexibly**.

✅ **Key ideas in Workflows:**
- Steps listen for and emit **Events**.
- Workflows enable **branching, loops, concurrency**, and **state management**.
- They are **agentic**: steps react dynamically based on incoming events.

---

## 📚 What We Cover in This Tutorial Series

Each notebook in this repo focuses on one important Workflow concept:

| Notebook | What it Covers |
|:---|:---|
| `Basic Workflow.ipynb` | How to build a basic event-driven workflow |
| `Branches and loops.ipynb` | How workflows can branch and loop dynamically |
| `Concurrent execution.ipynb` | How to run multiple steps at the same time (concurrency) |
| `Maintaining state.ipynb` | How workflows can hold shared memory and state |
| `Nested workflows.ipynb` | Running workflows inside other workflows (nested workflows) |
| `Observability.ipynb` | How to monitor, debug, and log what's happening inside workflows |
| `Streaming events.ipynb` | Streaming outputs live as the workflow runs |
| `Subclassing workflows.ipynb` | How to extend and customize workflows via subclassing |
| `Workflows from unbound functions.ipynb` | Building workflows without classes using standalone functions |

✅ All examples are **self-contained**, **easy to run**, and **designed for fast testing** in any JupyterLab or VSCode environment.

---

## 🧩 How to Get Started

1. Clone this repository.
2. Open any `.ipynb` notebook in JupyterLab or VS Code.
3. Install necessary dependencies:
   ```bash
   pip install llama-index python-dotenv

⚠️ Disclaimer
Some examples and conceptual materials in this repository were adapted from the official LlamaIndex documentation and examples, and reorganized to provide clearer step-by-step explanations.
These notebooks were prepared with the assistance of ChatGPT to simplify concepts, accelerate learning, and provide runnable, hands-on guides.

They are intended for educational and personal testing purposes only.
All original copyrights, trademarks, and intellectual property remain the property of LlamaIndex and their respective owners.

✅ Use these notebooks responsibly for learning and experimentation.

🎯 Motto:
"Build workflows fast. Understand them faster."