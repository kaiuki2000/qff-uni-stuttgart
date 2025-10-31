# Qiskit Fall Fest 2025 — University of Stuttgart (November 3–5, 2025)

**Qiskit Fall Fest** is a student-led hackathon and workshop series on quantum computing, hosted at universities worldwide in collaboration with **IBM Quantum**. The 2025 edition at the University of Stuttgart featured lectures, workshops, and a one-day hackathon.

---

## Repository Overview

This repository contains materials for the Qiskit Fall Fest 2025 workshops and challenges, including:

* `Notebook_1/prompt_1.ipynb` — Introduction to Qiskit 101; exercises for building, running, and measuring quantum circuits.
* `Notebook_2/prompt_2.ipynb` — Pirate-themed intermediate challenge inspired by the Elitzur–Vaidman interaction-free measurement. Participants detect “trapped” treasure chests without opening them.
* `Notebook_2/images/` — Supporting figures used in the notebooks.
* `README.md` — Setup, usage instructions, and participation guidelines.
* `BasQQiskit_Fall-Fest_2025_Slides.pdf` — Optional reference material that inspired the pirate-themed prompt.

---

## Getting Started

### 1. Install prerequisites

Create a Python environment (3.8+) and install dependencies:

```bash
# Create a virtual environment (optional but recommended)
python -m venv qff_env

# Activate it
# Windows
qff_env\Scripts\activate
# macOS / Linux
source qff_env/bin/activate

# Install dependencies
pip install -r requirements.txt
```

Minimal required packages include:

* `qiskit`, `qiskit-aer`, `qiskit-ibm-runtime`
* `numpy`, `matplotlib`
* `ipykernel`, `pylatexenc`
* (Optional: `jupyterlab` for interactive notebook use)

*Tip:* Version ranges are provided in `requirements.txt` to ensure reproducibility.

### 2. Run the notebooks

Open the notebooks in JupyterLab or VS Code and run cells in order. Some cells are intentionally left blank for you to implement your solutions.

### 3. Submission & Assessment

Participants should submit:

* Completed notebook(s) with code and explanations.
* 3–4 slides summarizing reasoning for each challenge (for the pirate-themed Notebook 2).

The top solution(s) will be invited to give a brief pitch during the award ceremony.

---

## Contribution Guidelines

We welcome contributions from students, researchers, and partners:

1. Fork this repository (or create a new branch if you have access).
2. Add your materials in a new folder or update existing notebooks with clear documentation.
3. Open a pull request describing your changes.

For text fixes or small improvements, feel free to open an issue.

---

## Partners & Sponsors

Supported by **IBM Quantum**, HQS Simulations, KIPU Quantum, Bosch, and the School for Talents at the University of Stuttgart.

---

## Contact

For inquiries, partnerships, or media requests:
🌐 [qiskit-fall-fest-bw.com](https://qiskit-fall-fest-bw.com)
📧 **Email:** [afonso.azenha@iti.uni-stuttgart.de](mailto:afonso.azenha@iti.uni-stuttgart.de)

---

## License

All code and example materials are licensed under the **MIT License**.
See the [`LICENSE`](LICENSE) file for details.

© 2025 University of Stuttgart — Qiskit Fall Fest Organizers

---

*Created for Qiskit Fall Fest 2025 — University of Stuttgart*
