# Automated Birthday Wisher Python

[![License: MIT](https://img.shields.io/badge/License-MIT-orange.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.8-black.svg)](https://www.python.org/downloads/release/python-380/)
![Version](https://img.shields.io/badge/version-v0.1-olive)

## Automated Birthday Wisher Python v0.1

The Automated Birthday Wisher Python (`main.py`) is a script designed to automatically send birthday wishes via email. It reads birthday information from a CSV file (`birthdays.csv`), checks if there are any birthdays today, and sends personalized birthday emails using predefined letter templates.

## Setup

To run and test the code, you need to update four places:

1. Change `MY_EMAIL` and `MY_PASSWORD` to your own email details.
2. Allow less secure apps in your email provider settings.
3. Update the `SMTP ADDRESS` to match your email provider.
4. Update `birthdays.csv` to contain today's month and day.

See the solution video in the 100 Days of Python Course for explanations.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/akumarm23/Day32-AutoBdayWisher.git
   cd Day32-AutoBdayWisher
   ```

2. Update the necessary details as mentioned in the setup.
3. Run the script:

   ```bash
   python main.py
   ```

4. Check the recipient's email for the birthday wish.

## Email Templates

- Email content is customized using predefined letter templates in the `letter_templates` directory.
- The script randomly selects one of the templates for each birthday.

## Data File

- Birthday data is stored in the `birthdays.csv` file.
- The script reads this file to identify birthdays for the day.

## Requirements

- Python 3.8
- `pandas` library (install with `pip install pandas`)

## Acknowledgments

Feel free to contribute and enhance the functionality of this Automated Birthday Wisher Python script! Happy automating!
