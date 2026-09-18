# SMIF Quantitative Division Repository

Welcome to the **SMIF Quantitative Division repository**.

This repository serves as the division's central file storage for **workshop materials, Jupyter notebooks, datasets, practice files, and supporting resources** used throughout the semester.

We will continue adding materials as the division progresses.

---

## Current Material

The current notebook is:

### `testing-material-quants-smif.ipynb`

This notebook is provided as an early reference point so you can familiarize yourself with the type of quantitative finance work we will be doing.

If you are **new to Python or `.ipynb` Jupyter Notebook files**, I strongly suggest opening the materials and experimenting with them now.

If you already have experience with Python and notebooks, review the sample content to get a feel for the workflow, calculations, visualizations, and level of analysis.

> **Important:** Download the **entire repository**, not only the notebook. The notebook depends on the CSV files included with it.

---

# Before We Begin

## 1. Download Anaconda

We will use **Anaconda / Conda throughout the semester** to manage Python, packages, environments, and Jupyter notebooks.

### [Download Anaconda](https://www.anaconda.com/download)

If you are unfamiliar with **Anaconda, Python environments, or the general setup process**, you can also follow this playlist from a professional with experience in **model development, model validation, and quantitative risk**:

### [Anaconda / Python Setup Playlist](https://www.youtube.com/watch?v=QXh_hdm8KfA&list=PLBfqPS8Xvt2AZGPZkBT0cahppnzKrjsqp)

---

# Division Environment

To keep everyone working with a consistent setup, the division will use the following environment:

| Setting | Division Standard |
|---|---|
| **Conda Environment** | `smif-quant` |
| **Python Version** | `3.14` |
| **Interface** | JupyterLab or VS Code |
| **Kernel** | `Python (smif-quant)` |

> ## ⚠️ Do not use Anaconda `base/root` for division work.

`base/root` is Anaconda's default environment.

Instead, we use a separate environment called:

```text
smif-quant
