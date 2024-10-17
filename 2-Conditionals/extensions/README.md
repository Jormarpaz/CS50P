# File Extensions

This project contains a Python script `extensions.py` that determines the MIME type of a file based on its extension.

## Description

The script `extensions.py` prompts the user to input a file name. It then normalizes the input by removing spaces and converting it to lowercase. The script checks the file extension and prints the corresponding MIME type. If the extension is not recognized, it prints "application/octet-stream".

## Usage

To run the script, use the following command in your terminal:

```sh
python extensions.py
```

You will be prompted to enter a file name. Based on your input, the script will respond with the appropriate MIME type.

## Example

```sh
$ python extensions.py
File Name: example.gif
image/gif
```

```sh
$ python extensions.py
File Name: document.pdf
application/pdf
```

```sh
$ python extensions.py
File Name: unknown.xyz
application/octet-stream
```

## Requirements

- Python 3.x

## Installation

Clone the repository to your local machine:

```sh
git clone https://github.com/yourusername/CS50P.git
cd CS50P/2-Conditionals/extensions
```

Run the script:

```sh
python extensions.py
```

## License

This project is licensed under the MIT License. See the [LICENSE](../LICENSE) file for details.
