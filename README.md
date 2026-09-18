SMIF Quantitative Division Repository
Welcome to the SMIF Quantitative Division repository.
This repository is the division's central file storage for workshop materials, Jupyter notebooks, datasets, practice files, and supporting resources used throughout the semester. We will continue adding materials as the division progresses.
---
Current Material
The current notebook is:
`testing-material-quants-smif.ipynb`
It is provided as an early reference point so you can familiarize yourself with the type of quantitative finance work we will be doing.
If you are new to Python or `.ipynb` Jupyter Notebook files, I strongly suggest opening the materials and experimenting with them now. If you already have experience with Python and notebooks, review the sample content to get a feel for the workflow, calculations, and level of analysis.
> **Important:** Download the **entire repository**, not only the notebook. The notebook depends on the CSV files included with it.
---
Before We Begin
1. Download Anaconda
We will use Anaconda / Conda throughout the semester to manage Python, packages, environments, and Jupyter notebooks.
Download Anaconda:  
https://www.anaconda.com/download
If you are not familiar with Anaconda, Python environments, or the general setup process, you can also follow this playlist from a professional with experience in model development, model validation, and quantitative risk:
Anaconda / Python Setup Playlist
---
Division Environment
To keep everyone working with the same setup, the division standard is:
Setting	Division Standard
Conda Environment	`smif-quant`
Python Version	`3.14`
Interface	JupyterLab or VS Code
Kernel	`Python (smif-quant)`
> **Do not use Anaconda `base/root` for division work.**
`base/root` is Anaconda's default environment. Instead, we use a separate environment called `smif-quant`.
Think of `smif-quant` as its own isolated Python workspace. It has its own Python version and packages, which helps prevent unrelated projects or package updates from interfering with the division's notebooks.
The exact file path of the environment will be different on each person's computer. That is normal. What matters is that you create the environment from this repository's `environment.yml` file and use the `Python (smif-quant)` kernel.
---
First-Time Setup
After installing Anaconda:
Click Code -> Download ZIP on this repository.
Extract the ZIP file. Do not work directly inside the ZIP.
Open Anaconda Prompt.
Navigate to the extracted repository folder.
Run:
```bash
conda env create -f environment.yml
```
Activate the environment:
```bash
conda activate smif-quant
```
Then either launch JupyterLab:
```bash
jupyter lab
```
or open the repository folder in your normal VS Code installation.
Open:
```text
testing-material-quants-smif.ipynb
```
Make sure the selected kernel is:
```text
Python (smif-quant)
```
Then run the notebook from the top.
If `Python (smif-quant)` does not appear
Run:
```bash
conda activate smif-quant
python -m ipykernel install --user --name smif-quant --display-name "Python (smif-quant)"
```
Then restart JupyterLab or VS Code and select `Python (smif-quant)`.
If you see `ModuleNotFoundError`
Before installing anything, check your kernel.
You are probably running the notebook with the wrong Python environment. The correct kernel is:
```text
Python (smif-quant)
```
Do not switch to `base`, a global Python installation, or another unrelated environment.
For a full beginner walkthrough and troubleshooting guide, see the detailed setup guide included in this repository.
---
Keep These Files Together
The first release is intended to stay together as one project folder:
```text
smif-quant-files/
|
|-- README.md
|-- environment.yml
|-- testing-material-quants-smif.ipynb
|-- Amazon.csv
|-- JPM.csv
|-- stock_prices.csv
|-- stock_data.csv
|-- anaconda_and_python_BEGINNER_setup_guide_quants.txt
```
The notebook uses relative file paths, so you can move the whole repository folder anywhere on your computer. Do not casually rename or separate the CSV files from the notebook.
---
Suggested Reading & Practice
A suggested reference for the division is:
Quantitative Finance with Case Studies in Python
A Practical Guide to Investment Management, Trading and Financial Engineering  
Chapman and Hall/CRC Financial Mathematics Series
This book will serve as one of the division's reference and practice resources for quantitative finance applications in Python.
Please purchase the book or obtain a legal digital copy through the publisher, a library, or another authorized source.
Companion GitHub Repository
The book also has a companion GitHub repository containing Python code, examples, and supporting materials that we may reference in future workshops and practice sessions:
Quantitative Finance with Case Studies in Python — GitHub Repository
If you would like to review material ahead of time, feel free to explore the repository and experiment with the examples.
---
Community
The Quantitative Division is meant to be collaborative.
Please feel free to:
Share ideas
Ask questions
Discuss concepts
Suggest projects
Share useful resources
Propose topics for future workshops
Work on projects together with other members
The goal is not only to learn the material individually, but to build, test, discuss, and improve ideas together as a group.
