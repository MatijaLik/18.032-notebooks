# 18.032 Interactive Notebooks

This repository contains interactive Jupyter notebooks that serve as supplementary material for **18.032**, MIT's class in differential equations. They are designed to help you explore concepts interactively and deepen your understanding of the course material. New notebooks will be added roughly on a bi-weekly basis throughout the semester.

If you spot errors or have suggestions for improvements, please contact the class UA, Matija Likar, whose email can be found in the course syllabus.

## Table of Contents
- [Online Access](#online-access)
- [Notebook Index](#notebook-index)
- [Feedback](#feedback)
- [Local Setup](#local-setup)
  - [Prerequisites](#prerequisites)
  - [Installation Steps](#installation-steps)
  - [Troubleshooting](#troubleshooting)

## Online Access

You can access the notebooks directly in your browser using Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MatijaLik/18.032-notebooks/main?urlpath=%2Fdoc%2Ftree%2Fnotebooks%2F00-index.ipynb)

Click the badge above to launch an interactive Jupyter environment with all notebooks ready to use. 

**Important:** You should launch the Binder environment anew, using the badge above, each time new notebooks are added to the repository. Also, you should download your work to your local machine before leaving the Binder environment if you want to keep it. Alternatively, you can use the [local setup instructions](#local-setup) below to run the notebooks locally on your computer.

## Notebook Index
| Index | Notebook | Date |
|-------|----------|------|
| 1 | [Logistic map](./notebooks/01-logistic-map.ipynb) | 2026-02-04 |

## Local Setup

To run and edit the notebooks locally on your computer, follow these steps:

### Prerequisites

- Python 3.11 or above (Python 3.11 recommended)
  - Note: The Binder environment uses Python 3.11 (specified in `runtime.txt`). For best compatibility, use Python 3.11 or higher locally.
- pip (Python package installer)


### Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MatijaLik/18.032-notebooks.git
   cd 18.032-notebooks
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   ```
   
   If you have multiple Python versions and want to use Python 3.11 specifically:
   - On Linux/Mac:
     ```bash
     python3.11 -m venv venv
     ```
   - On Windows:
     ```bash
     py -3.11 -m venv venv
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

- Make sure you're using Python 3.11 or above (Python 3.11 recommended to match the Binder environment). Check your Python version:
  ```bash
  python --version
  ```
  
  If you need to install Python 3.11 or a newer version:
  - **Linux:** 
    ```bash
    sudo apt-get update
    sudo apt-get install python3.11 python3.11-venv
    ```
  - **macOS:** 
    ```bash
    brew install python@3.11
    ```
  - **Windows:** Download Python 3.11 or newer from [python.org](https://www.python.org/downloads/)