Password Cracker Tool

Overview:
The Password Cracker is a basic proof-of-concept tool designed for educational purposes. It allows users to recover original passwords from hashes using various cracking techniques.

Requirements:

Python Version: Ensure you have Python 2.7 installed to run the script. You can download it from https://www.python.org/downloads/release/python-2716/.
How to Use:
To run the Password Cracker, execute the following command in your terminal:
python password_cracker.py <hash> <attack>

Arguments:
<hash>: The hash you want to crack.
<attack>: The cracking technique you wish to apply.
Optional Arguments:
Different attacks support additional optional parameters. You can view all available options with the command:
python password_cracker.py --help

Available Cracking Techniques:
1. Brute Force:
Tries all possible alphanumeric passwords with a length of up to --length_max.
2. Dictionary Attack:
Uses passwords contained in a specified dictionary file provided by --dictionary.
3. Dictionary with Replacements:
Similar to the dictionary attack, but for each password in the dictionary, it also tries variations based on character replacements specified by --replacements.
4. Targeted Attack:
Attempts all possible permutations of subsets of a list of words specified by --words.


