Python Email Sender with HTML Formatting

This Python script allows you to send emails with HTML formatting using the smtplib library. It prompts the user to enter the recipient's email address and the message content, and then sends the email with the specified formatting.

Features:

1) Supports HTML formatting for the email content.
2) Allows customization of font size, color, and image display.
3) Uses Gmail SMTP server for sending emails.
4) Securely encrypts the connection using TLS.
5) Handles authentication using SMTP credentials.

Instructions:

1) Make sure you have the required libraries installed: smtplib, email.
2) Replace the smtp_password variable with the correct password for the sender's Gmail account.
3) Run the script and enter the recipient's email address and the message content when prompted.
4) The script will send the email with the specified HTML formatting.
5) Check the console output for the status of the email sending process.

Note:

If you encounter issues with authentication while using a Google account, such as an SMTPAuthenticationError, it could be due to the following reasons:

• Incorrect username or password: Double-check that you have entered the correct credentials for the SMTP server.

• 2-Step Verification enabled: If you have 2-Step Verification enabled on your Google account, you will need to generate an
application-specific password to use in the script. 

• Follow the instructions provided by Google to generate the password and replace the smtp_password variable with the application-specific password.




