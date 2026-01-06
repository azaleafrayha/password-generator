# Password Generator
This project is based on FreeCodeCamp (FCC) Scientific Computing with Python curriculum. This tool is to help generate passwords that are actually hard to crack, say goodbye to 'password123' !

It's not just random gibberish, it uses **Regex** to make sure every password has the right mix of symbols, numbers, and letters. And this is what it looks like when I run the code:

<p align="center">
    <img src="c:\Users\LENOVO\Pictures\Screenshots\Screenshot (171).png" width="1000">
</p>

## Project Structure
Inside this repository, you will find:
* `generate.py` — The main Python script to generate password.
* `README.md` — The documentation you are reading right now.

## Features and things I have learned from this project:
* **Python module**: How to use `import string`, `random`, and `secrets`. Now I understand that the dot `.` is used to "access" functions inside a module.

* **Variables & Data Types**: The difference between list `[]`, tuple `()`, and string `''`.

* **Looping**: Learned how to use `for _ in range()`. Using an underscore `_` as a throwaway variable when the index isn't needed.

* **Dunder (Double Underscore)**: Learned how to use `if __name__ == '__main__':` to use the function when this file got imported to another file.

* **Regular Expression (regex)**: 
    * The usage of `re.compile()` to prepare search patterns, `[a-z]` for matching lowercase letters, and `[0-9]` for finding digits.

    * The analogy of using `\n` in **Normal String** and **Raw String**

        * **Normal String**: Python is like a "helpful" assistant who sees `\n` and thinks, *"Oh! He wants a New Line (`Enter key`) here!"* and he actually hits the `Enter key`.

        * **Raw String**: Python is like a photocopier. It doesn't think. It just sees a `\` and a `n`, and it prints exactly a `\` and a `n`.

    * The difference between `re.search()` (finds the first match) and `re.findall()` (collects all matches)