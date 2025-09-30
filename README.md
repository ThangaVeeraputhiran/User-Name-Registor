# User-Name-Registor
Username Register Project

This is a simple user registration system built with Python. The idea is to mimic what happens when a new user signs up in a mobile app — their name, email, and password need to be checked before the account is created.

I used helper functions (validate_name, validate_email, validate_password) to make sure the input is correct and safe. Once everything passes the checks, the user gets registered and their details are stored. If something is wrong, an error is raised so the user knows what to fix.

What it does

✔️ Checks if the name is valid

✔️ Validates the email format (with top-level domains)

✔️ Makes sure the password is strong enough

✔️ Handles errors and shows clear messages

✔️ Returns the registered user details if everything is correct

How it works

The user enters their details.

Each field is validated (name → email → password).

If any field fails, a ValueError is raised.

If all fields pass, the user is successfully registered.

Example
