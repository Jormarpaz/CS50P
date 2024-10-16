# Week 5 Projects: Libraries

This week's projects focus on utilizing various Python libraries to accomplish different tasks. Below is a brief overview of each project, their purpose, and how to use them.

## Projects

### 1. `adieu.py`

This script takes multiple names as input and prints a farewell message using the `inflect` library to handle proper grammar.

#### Usage

```bash
python adieu.py
```

Enter names one by one, pressing Enter after each name. To end input, use `Ctrl+D` (EOF).

### 2. `bitcoin.py`

This script fetches the current price of Bitcoin in USD from the CoinDesk API and calculates the total cost for a given amount of Bitcoins.

#### Usage

```bash
python bitcoin.py <amount>
```

Replace `<amount>` with the number of Bitcoins you want to check the price for.

### 3. `emojize.py`

This script converts text with emoji aliases into actual emojis using the `emoji` library.

#### Usage

```bash
python emojize.py
```

Enter a string with emoji aliases (e.g., `:smile:`) and the script will output the string with actual emojis.

### 4. `figlet.py`

This script generates ASCII art from text using the `pyfiglet` library. You can specify a font or let the script choose a random one.

#### Usage

```bash
python figlet.py [-f | --font <fontname>]
```

If no font is specified, a random font will be used. Enter the text you want to convert to ASCII art when prompted.

### 5. `game.py`

This script is a number guessing game where the user has to guess a randomly generated number within a specified range.

#### Usage

```bash
python game.py
```

Enter a level (positive integer) to set the range, then guess the number until you get it right.

### 6. `professor.py`

This script simulates a simple math quiz where the user has to answer addition problems. The difficulty level determines the range of numbers used in the problems.

#### Usage

```bash
python professor.py
```

Enter a level (1, 2, or 3) to set the difficulty, then answer the addition problems. The score is displayed at the end.

## Conclusion

These projects demonstrate the use of various Python libraries to perform different tasks, from handling text and numbers to interacting with web APIs. Experiment with each script to understand how they work and how to use these libraries in your own projects.
