# Email-Slicer
The code validates and slices an email address into username and domain using regular expressions. It checks if the input matches the email pattern before slicing.

Here's a step-by-step description of the provided code for slicing and validating an email address:

Import the re Module: The code starts by importing the re module, which provides support for regular expressions in Python.

Define the isValidEmail Function: This function takes an email address as input and returns True if the email is valid according to a specified regular expression, otherwise it returns False. The regular expression pattern used checks for the general structure of an email address.

Regular Expression for Email Validation: The regular expression pattern regex is defined using a raw string literal (r). This pattern is designed to match valid email addresses according to common conventions.

Check Email Validity: The isValidEmail function uses the re.fullmatch() function to check if the input email matches the defined regular expression pattern. If it does, the function returns True, indicating that the email is valid; otherwise, it returns False.

Input Email Address: The user is prompted to input their email address using the input() function. The entered email address is stored in the variable email.

Validate the Email Address: The entered email address is passed to the isValidEmail function to check its validity. If the email is valid, the code proceeds to the next steps; otherwise, it prints "Invalid Email!" and terminates.

Slice the Email Address: If the email address is valid, the code extracts the username and domain parts by using string slicing. The username is everything before the '@' symbol, and the domain is everything after the '@' symbol.

Print the Username and Domain: Finally, the code prints the extracted username and domain parts of the email address.

This code provides a simple example of how to validate and extract components from an email address using regular expressions in Python.

DEMO:

![image](https://github.com/arshasuresh03/Email-Slicer/assets/160167081/71c1960c-3013-4cab-8ce7-e68dd205cbd2)
