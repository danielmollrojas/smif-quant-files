# SMIF Quantitative Division Repository

Welcome to the **SMIF Quantitative Division repository**.

This repository serves as the division's central file storage for **workshop materials, Jupyter notebooks, datasets, practice files, and supporting resources** used throughout the semester.

We will continue adding materials here as the division progresses.

---

## Current Material

The current notebook:

**`testing-material-quants-smif.ipynb`**

is provided as an early reference point so you can familiarize yourself with the type of quantitative finance work we will be doing.

If you are **new to Python or `.ipynb` Jupyter Notebook files**, I strongly suggest opening the materials and experimenting with them now.

If you already have experience with Python and notebooks, take some time to review the sample content and get a feel for the workflow, calculations, and level of analysis.

---

## Before We Begin

### Download Anaconda

We will be using **Anaconda throughout the semester** to manage Python, packages, environments, and Jupyter notebooks.

**Download Anaconda here:**

[Download Anaconda](https://www.anaconda.com/download)

If you are not familiar with **Anaconda, Python environments, or the general setup process**, you can also follow the playlist below from a professional with experience in **model development, model validation, and quantitative risk**:

[Anaconda / Python Setup Playlist](https://www.youtube.com/watch?v=QXh_hdm8KfA&list=PLBfqPS8Xvt2AZGPZkBT0cahppnzKrjsqp)

---

## Division Environment

To keep everyone working with a consistent setup, the division will use the following environment:

| Setting | Division Standard |
|---|---|
| **Conda Environment** | `smif-quant` |
| **Python Version** | `3.14` |
| **Interface** | JupyterLab or VS Code |
| **Kernel** | `Python (smif-quant)` |

> **Do not use Anaconda `base/root` for division work.**

### Why are we using a separate environment?

When Anaconda is installed, it includes a default environment commonly called **`base`** or **`root`**.

Rather than installing every Python package into that main environment, we will create a dedicated environment called:

```text
smif-quant
