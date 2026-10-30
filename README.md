# Password Generator 🔐

A simple Python-based password generator that creates random passwords based on the user's preferred length and character requirements.

## Features

- Set a minimum password length.
- Choose whether to include numbers.
- Choose whether to include special characters.
- Automatically ensures the generated password meets the selected criteria.
- Uses Python's built-in `random` and `string` modules.

## Technologies Used

- **Python**
- `random` – Selects random characters.
- `string` – Provides letters, digits, and special characters.

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/password-generator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd password-generator
   ```

3. Run the Python file:

   ```bash
   python3 password_generator.py
   ```

## Example Output

```text
Enter the minimum length: 12
Do you want to have numbers (y/n)? y
Do you want to have special characters (y/n)? y

The generated password is: aB7@kP2#mQ9!
```

*Note: The generated password will be different each time.*

## Concepts Practiced

- Python functions
- While loops
- Conditional statements
- User input
- String manipulation
- Random character selection
- Boolean variables

## Future Improvements

- Add an option to generate multiple passwords.
- Allow users to copy passwords directly.
- Implement stronger password generation using Python's `secrets` module.

## Author

Created as a Python practice project.
