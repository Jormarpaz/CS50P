# Week 7 Projects

This week's projects focus on file handling and manipulation using Python. Below are the details of each project, their names, and instructions on how to use them.

## Projects

### 1. `lines.py`

Counts the number of lines of code in a Python file, excluding comments and blank lines.

#### Usage

```sh
python lines.py filename.py
```

- `filename.py`: The Python file to count lines of code.

### 2. `pizza.py`

Reads a CSV file containing pizza data and displays it in a formatted table using the `tabulate` library.

#### Usage

```sh
python pizza.py pizza.csv
```

- `pizza.csv`: The CSV file containing pizza data.

### 3. `scourgify.py`

Reads a CSV file with student names and houses, then writes a new CSV file with the names split into first and last names.

#### Usage

```sh
python scourgify.py input.csv output.csv
```

- `input.csv`: The input CSV file with student data.
- `output.csv`: The output CSV file with formatted student data.

### 4. `shirt.py`

Overlays a shirt image onto another image and saves the result.

#### Usage

```sh
python shirt.py input.JPEG/PNG output.JPEG/PNG
```

- `input.JPEG/PNG`: The input image file.
- `output.JPEG/PNG`: The output image file with the shirt overlay.

## Requirements

- Python 3.x
- Required libraries: `csv`, `sys`, `os`, `tabulate`, `PIL` (Pillow)

## Installation

Install the required libraries using pip:

```sh
pip install tabulate pillow
```

## Notes

- Ensure that the input files exist and have the correct extensions.
- For `shirt.py`, ensure that `shirt.png` is available in the same directory.
