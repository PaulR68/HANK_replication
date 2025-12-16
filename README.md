# HANK_replication
A replication and extension project of "Fiscal and Monetary Policy with Heterogeneous Agents" (Auclert, Rognlie, Straub 2025)
# HANK Replication Project: Fiscal and Monetary Policy with Heterogeneous Agents

This repository contains the replication code and an extension of the influential paper:

> **Auclert, Adrien, Ludvig W. Rognlie, and Gabriel E. Straub (2024). "Fiscal and Monetary Policy with Heterogeneous Agents."**

The paper establishes a canonical HANK model to analyze how household heterogeneity fundamentally alters the transmission channels of monetary and fiscal policies.

---

## Core Results Verified

* **Fiscal Policy:** Highly effective when deficit-financed, provided the transfers target high-MPC (Marginal Propensity to Consume) agents.
* **Monetary Policy:** Exhibits **"Monetary Equivalence"** (same aggregate output response as standard NK), but operates primarily through the **indirect labor income channel**.
* **Inequality:** Distributional analysis confirms a significant concentration of wealth following fiscal shocks (the *Trickling Up* phenomenon).

---

##  Repository Structure and Dependencies

This project is built upon the authors' original source code.

### 1. Authors' Code Dependency

The core model functions are **not** included in this repository. You must integrate the original authors' codebase.

 **Authors' Source Code:** [shade-econ/annual-review](https://github.com/shade-econ/annual-review?tab=readme-ov-file)

**Action Required:** Download or clone the authors' repository and ensure the necessary files are present in your working environment for the replication code to run successfully.

### 2. Repository Files

Your specific project files are organized as follows:

| File/Folder | Description |
| :--- | :--- |
| `Replication.ipynb` | **Main Execution Notebook.** Contains the code to run the core IRF (Impulse Response Function) replication and the **Extension** analyses (e.g., dynamic evolution of inequalities). |
| `Presentation/` | Contains the final presentation slides (e.g., LaTeX/PDF) detailing the paper summary, model structure, calibration, and all generated figures. |

---

##  How to Run the Project

1.  Clone this repository.
2.  Ensure all Python dependencies (NumPy, SciPy, etc.) and the authors' model files are correctly set up.
3.  Open and run the `Replication.ipynb` notebook to execute the simulations.

