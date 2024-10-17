# Deep Thought

This project contains a Python script `deep.py` that prompts the user for the answer to the Great Question of Life, the Universe, and Everything. Depending on the user's input, it will respond with either "Yes" or "No".

## Description

The script `deep.py` asks the user to input their answer to the Great Question of Life. It then normalizes the input by removing spaces and converting it to lowercase. The script checks if the input matches any of the accepted answers ("42", "forty-two", or "fortytwo") and prints "Yes" if it does. Otherwise, it prints "No".

## Usage

To run the script, use the following command in your terminal:

```sh
python deep.py
```

You will be prompted to enter your answer. Based on your input, the script will respond accordingly.

## Example

```sh
$ python deep.py
Answer to the Great Question of Life: 42
Yes
```

```sh
$ python deep.py
Answer to the Great Question of Life: forty-two
Yes
```

```sh
$ python deep.py
Answer to the Great Question of Life: 43
No
```

## Requirements

- Python 3.x

## Installation

Clone the repository to your local machine:

```sh
git clone https://github.com/yourusername/CS50P.git
cd CS50P/2-Conditionals/deep
```

Run the script:

```sh
python deep.py
```

## License

This project is licensed under the MIT License. See the [LICENSE](../LICENSE) file for details.
