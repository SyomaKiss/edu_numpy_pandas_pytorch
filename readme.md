# Installation Instructions

## Prerequisites

- Python 3.9 or higher
- [Poetry](https://python-poetry.org/docs/#installation) for dependency management

## Setup


2. Install dependencies using Poetry:
   ```bash
   poetry install
   ```

3. Activate the Poetry virtual environment:
   ```bash
   poetry shell
   ```

4. Install the Jupyter kernel in the Poetry environment:
   ```bash
   poetry run python -m ipykernel install --user --name=Numpy_Edu
   ```

## Usage

To run Jupyter Lab:
```bash
poetry run jupyter lab
```



