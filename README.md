# 18.032 Interactive Notebooks

This repository contains interactive Jupyter notebooks that serve as supplementary material for **18.032**, MIT's class in differential equations.

## Online Access

You can access the notebooks directly in your browser using Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MatijaLik/18.032-notebooks/master?urlpath=%2Fdoc%2Ftree%2Fnotebooks%2F00-index.ipynb)

Click the badge above to launch an interactive Jupyter environment with all notebooks ready to use.

## Local Setup

To run and edit the notebooks locally on your computer, follow these steps:

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)


### Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MatijaLik/18.032-notebooks.git
   cd 18.032-notebooks
   ```

2. **Create a virtual environment :**
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment:**
   - On Linux/Mac:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Launch Jupyter:**
   ```bash
   jupyter lab
   ```
   
   Or if you prefer the classic Jupyter Notebook interface:
   ```bash
   jupyter notebook
   ```

6. **Open the index notebook:**
   Navigate to `notebooks/00-index.ipynb` in the Jupyter interface to see all available notebooks.

### Troubleshooting

- If you encounter issues with `jupyter lab`, try installing it explicitly:
  ```bash
  pip install jupyterlab
  ```

- Make sure you're using Python 3.8 or higher. Check your Python version:
  ```bash
  python --version
  ```
