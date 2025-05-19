Regex Validator – Python Script Welcome to this simple yet handy Python script designed to validate common data formats using Regular Expressions (regex). If you're dealing with email addresses, URLs, phone numbers, or currency values and want a quick way to check their validity, this script has got you covered.

What It Does This script uses Python’s re module to validate:

Emails (e.g. user@example.com)

URLs (e.g. https://www.example.com)

Phone Numbers (e.g. (123) 456-7890, 123-456-7890, etc.)

Currency Amounts (e.g. $1,234.56)

It also includes a test suite with sample inputs and prints whether each example is valid or not.

File Overview Regex-Data.py:

1. is_valid_email(email) – Checks if an email address is valid.

2. is_valid_url(url) – Checks if a URL is valid.

3. is_valid_phone(phone) – Checks if a US-style phone number is valid.

4. is_valid_currency(amount) – Checks if a currency string follows the $X,XXX.XX format.

A sample dictionary test_data with various examples.

For-loops that run validations on the test data and print out results.

Make sure you have Python installed (3.x) in order to be able to run this file.

Open a terminal and run Regex-Data.py:
 
You'll see output showing which entries passed or failed validation

