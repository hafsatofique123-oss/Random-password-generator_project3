# Random Password Generator (Python)

A simple Python project that generates a random and secure password using letters, numbers, and special characters. This project demonstrates the use of Python's built-in `random` and `string` modules along with list comprehensions.

## Features

* Generates random passwords
* Includes uppercase and lowercase letters
* Includes digits (0-9)
* Includes special characters
* Uses list comprehension for concise code
* Beginner-friendly project

## How It Works

The program:

1. Imports the `random` and `string` modules.
2. Creates a pool of characters containing:

   * Alphabet letters (A-Z, a-z)
   * Digits (0-9)
   * Special characters (!, @, #, $, etc.)
3. Sets the desired password length.
4. Randomly selects characters from the pool.
5. Combines the selected characters into a password.
6. Displays the generated password.

## Technologies Used

* Python 3
* random module
* string module
* List Comprehension

## Code Highlights

```python
charVal = string.ascii_letters + string.digits + string.punctuation

password = "".join(
    [random.choice(charVal) for i in range(pass_len)]
)
```

## Example Output

```text
Generated Password:
A@7kP#2m
```

*Note:* The password will be different each time the program runs.

## How to Run

1. Install Python 3.
2. Save the code in a file named `password_generator.py`.
3. Open Terminal or Command Prompt.
4. Run the program:

```bash
python password_generator.py
```

## Learning Concepts

This project helps beginners learn:

* Python Modules
* Random Number Generation
* String Manipulation
* List Comprehensions
* Loops
* Password Generation Logic

## Future Improvements

* Allow user-defined password length
* Add options for strong or weak passwords
* Exclude confusing characters (e.g., O and 0)
* Generate multiple passwords at once
* Create a graphical user interface (GUI)

## License

This project is for educational purposes.
