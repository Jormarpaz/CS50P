# CS50P Week 6: Unit Tests

This week's projects focus on writing unit tests for various Python functions. Below are the details of each project, their purpose, and how to use them.

## Projects

### 1. `test_bank.py`

This project tests the `value` function from the `bank` module. The `value` function assigns a value to different greetings.

#### How to Use

1. Ensure you have the `bank` module with the `value` function.
2. Run the tests using pytest:

    ```sh
    pytest test_bank.py
    ```

### 2. `test_fuel.py`

This project tests the `convert` and `gauge` functions from the `fuel` module. The `convert` function converts a fraction to a percentage, and the `gauge` function returns a fuel gauge reading based on the percentage.

#### How to Use

1. Ensure you have the `fuel` module with the `convert` and `gauge` functions.
2. Run the tests using pytest:

    ```sh
    pytest test_fuel.py
    ```

### 3. `test_plates.py`

This project tests the `is_valid` function from the `plates` module. The `is_valid` function checks if a given license plate is valid based on specific criteria.

#### How to Use

1. Ensure you have the `plates` module with the `is_valid` function.
2. Run the tests using pytest:

    ```sh
    pytest test_plates.py
    ```

### 4. `test_twttr.py`

This project tests the `shorten` function from the `twttr` module. The `shorten` function removes vowels from a given string.

#### How to Use

1. Ensure you have the `twttr` module with the `shorten` function.
2. Run the tests using pytest:

    ```sh
    pytest test_twttr.py
    ```

## Running All Tests

To run all tests for the week, navigate to the directory containing the test files and run:

```sh
pytest
```

This will execute all the test files and provide a summary of the results.
