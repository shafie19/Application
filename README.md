# Application
# Personal Programming Code Example

This repository showcases a programming solution that highlights my coding skills and logical thinking. It is part of my application for a scholarship and demonstrates my ability to solve problems efficiently.

## Contents
- [Palindrome Checker](./Example1_PalindromeChecker/): A Python program to check if a given string is a palindrome.

## Contact
For questions or additional examples, feel free to reach out: [shafieabdulkadir441@gmamil..com](mailto:your-email@example.com)

## Example Input/Output
- **Input**: `racecar`  
**Output**: `The string is a palindrome!`  
- **Input**: `hello`  
**Output**: `The string is not a palindrome.`
def is_palindrome(string):
    """
    Checks if a given string is a palindrome.
    :param string: Input string to check
    :return: True if palindrome, False otherwise
    """
    return string == string[::-1]

if __name__ == "__main__":
    user_input = input("Enter a string: ")
    if is_palindrome(user_input):
        print("The string is a palindrome!")
    else:
        print("The string is not a palindrome.")

