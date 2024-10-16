# Week 9 Projects: Object-Oriented Programming

This week, we focus on Object-Oriented Programming (OOP) concepts through three projects: `jar.py`, `seasons.py`, and `shirtificate.py`. Below is a brief overview of each project and instructions on how to use them.

## Projects Overview

### 1. Jar.py

`jar.py` simulates a cookie jar with a specified capacity. You can deposit and withdraw cookies from the jar.

#### Usage

1. **Initialization**: Create a `Jar` object with a specified capacity (default is 12).

    ```python
    jar = Jar(capacity=10)
    ```

2. **Deposit Cookies**: Add cookies to the jar.

    ```python
    jar.deposit(5)
    ```

3. **Withdraw Cookies**: Remove cookies from the jar.

    ```python
    jar.withdraw(3)
    ```

4. **Check Size**: Get the current number of cookies in the jar.

    ```python
    print(jar.size)
    ```

### 2. Seasons.py

`seasons.py` calculates the number of minutes you have lived based on your birthdate and prints the result in words.

#### Usage

1. Run the script and input your birthdate in the format `YYYY-MM-DD`.

    ```sh
    python seasons.py
    ```

2. The script will output the number of minutes you have lived in words.

### 3. Shirtificate.py

`shirtificate.py` generates a PDF certificate with your name on a shirt image.

#### Usage

1. Run the script and input your name.

    ```sh
    python shirtificate.py
    ```

2. The script will generate a `shirtificate.pdf` file with your name on it.

## Requirements

- Python 3.x
- Required libraries:
  - `fpdf`
  - `inflect`

Install the required libraries using pip:

```sh
pip install fpdf inflect
```

## Running the Scripts

To run any of the scripts, navigate to the directory containing the script and use the following command:

```sh
python script_name.py
```

Replace `script_name.py` with the name of the script you want to run.

Enjoy exploring Object-Oriented Programming with these projects!