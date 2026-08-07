# Number Guessing Game

A simple command-line **Number Guessing Game** written in Python.

The computer randomly selects a number between 1 and 100.  
You have to guess the number, and the game will guide you with "Higher" or "Lower" hints until you find the correct number.

## How to Play

1. Run the game
2. Enter a number between 1 and 100
3. Follow the hints:
   - "Higher number please" → Guess a bigger number
   - "Lower number please" → Guess a smaller number
4. Keep guessing until you find the correct number
5. The game will show how many attempts you took

## Features

- Random number generation (1 to 100)
- Helpful higher/lower hints
- Tracks number of attempts
- Simple and clean command-line interface
- Beginner-friendly code

## Requirements

- Python 3.6 or higher
- No external libraries required (uses only Python standard library)

## Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/abdulbasitbehlim/YourRepoName.git
   cd YourRepoName
   ```

2. Run the game:
   ```bash
   python main.py
   ```
   or
   ```bash
   python3 main.py
   ```

## Project Structure

```
Number-Guessing-Game/
├── main.py              # Main game file
├── README.md            # Project documentation
├── LICENSE              # MIT License
├── .gitignore           # Git ignore rules
└── requirements.txt     # Dependencies (none required)
```

## Example

```
Guess the number: 50
Higher number please
Guess the number: 75
Lower number please
Guess the number: 63
You have guessed the number 63 correctly in 3 attempts
```

## Contributing

Feel free to fork this repository, suggest improvements, or submit pull requests.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
