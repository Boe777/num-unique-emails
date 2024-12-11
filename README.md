
# Num Unique Emails

This repository contains a Python function that calculates the number of unique email addresses by handling local part normalization (removing periods and ignoring text after a '+') and case insensitivity. Inspired by Leetcode 929.

## Functionality

The function `numUniqueEmails(emails)` processes a list of email addresses and returns the count of unique emails based on the above criteria.

### Usage

1. Clone the repository:
   ```
   git clone https://github.com/Boe777/num-unique-emails.git
   ```
    
2. Install dependencies (optional):
   ```
   pip install -r requirements.txt
   ```

3. Run the script:
   ```python
   from num_unique_emails import numUniqueEmails

   emails = [
       "test.email+spam@gmail.com",
       "test.email@gmail.com",
       "test.email@Gmail.com",
       "testemail@gmail.com",
       "Test.Email+filter@gmail.com",
       "test.email123@gmail.com"
   ]

   print(numUniqueEmails(emails))
   ```

## Tests

Tests for the function can be found in the `tests/test_num_unique_emails.py` file. To run the tests, you can use:

```
pytest
```

## License

MIT License
