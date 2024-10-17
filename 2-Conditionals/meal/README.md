# Meal Time

This project contains a Python script `meal.py` that determines the meal time based on the user's input of the current time.

## Description

The script `meal.py` prompts the user to input the current time in the format `HH:MM`. It then converts the time to a float representing the hour and checks if it falls within the predefined meal times. The script prints "breakfast time", "lunch time", or "dinner time" based on the input.

## Usage

To run the script, use the following command in your terminal:

```sh
python meal.py
```

You will be prompted to enter the current time. Based on your input, the script will respond with the appropriate meal time.

## Example

```sh
$ python meal.py
What time is it: 07:30
breakfast time
```

```sh
$ python meal.py
What time is it: 12:00
lunch time
```

```sh
$ python meal.py
What time is it: 18:45
dinner time
```

## Requirements

- Python 3.x

## Installation

Clone the repository to your local machine:

```sh
git clone https://github.com/yourusername/CS50P.git
cd CS50P/2-Conditionals/meal
```

Run the script:

```sh
python meal.py
```

## License

This project is licensed under the MIT License. See the [LICENSE](../LICENSE) file for details.
