# Entity Matching Project Setup

This guide outlines the steps required to set up the Python environment for the Entity Matching project. 

## Requirements

- Python 3.8 or newer
- pip (Python package installer)

## Environment Setup

Follow these steps to set up your project environment:

### 1. Clone the Repository

First, clone the repository to your local machine using Git:

```bash
git clone https://github.com/your-repository/entity_matching.git
cd entity_matching
```

### 2. Create a Virtual Environment

Create a new virtual environment named `entity_matching` using Python. This helps to keep dependencies required by different projects separate by creating isolated python virtual environments for them.

```bash
# On macOS and Linux:
python3 -m venv entity_matching

# On Windows:
python -m venv entity_matching
```

### 3. Activate the Virtual Environment

Before you can start installing the required packages, you'll need to activate the virtual environment.

```bash
# On macOS and Linux:
source entity_matching/bin/activate

# On Windows:
entity_matching\Scripts\activate
```

### 4. Install Required Packages

Install all the required packages using `pip` and the `requirements.txt` file provided in the repository.

```bash
pip install -r requirements.txt
```

## Deactivate the Virtual Environment

When you are done working in the virtual environment for the moment, you can deactivate it by running:

```bash
deactivate
```

This will revert your python environment to normal.

## Troubleshooting

If you encounter any issues during the installation of packages, ensure your pip is up-to-date:

```bash
pip install --upgrade pip
```