# Birthday Email Sender

This project is a simple script that sends automated birthday emails to your friends and family using Python. It reads from an excel sheet that contains all of your friends’ details and checks if today is their birthday. If so, it sends them an email before making a note in your spreadsheet to say they’ve received their email.

## Requirements

This program uses the following modules:

- smtplib
- EmailMessage
- datetime
- pandas
- openpyxl

To install these modules, run the following command in your terminal:

```bash
pip install pandas openpyxl
```


## Usage

1. Clone this repository to your local machine.
2. Open the `birthday_email_sender.py` script in your preferred text editor.
3. Add your email address and password to the designated fields in the script.
4. Update the file path for the `birthday.xlsx` spreadsheet to match the location of the file on your local machine.
5. Customize the email message to your liking, making sure to include the appropriate placeholders for the recipient's name and age.
6. Save the changes to the script.
7. Run the script in your terminal by typing `python birthday_email_sender.py`.

## Author

Chukwudi Ofoma

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
