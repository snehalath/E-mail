Python Email Sender with HTML Formatting

This Python script allows you to send emails with HTML formatting using the smtplib library. It prompts the user to enter the recipient's email address and the message content, and then sends the email with the specified formatting.

Features:

1)Supports HTML formatting for the email content.
2)Allows customization of font size, color, and image display.
3)Uses Gmail SMTP server for sending emails.
4)Securely encrypts the connection using TLS.
5)Handles authentication using SMTP credentials.

Instructions:

1)Make sure you have the required libraries installed: smtplib, email.
2)Replace the smtp_password variable with the correct password for the sender's Gmail account.
3)Run the script and enter the recipient's email address and the message content when prompted.
4)The script will send the email with the specified HTML formatting.
5)Check the console output for the status of the email sending process.

Note:
If you encounter issues with authentication while using a Google account, such as an SMTPAuthenticationError, it could be due to the following reasons:

Incorrect username or password: Double-check that you have entered the correct credentials for the SMTP server.
2-Step Verification enabled: If you have 2-Step Verification enabled on your Google account, you will need to generate an application-specific password to use in the script. Follow the instructions provided by Google to generate the password and replace the smtp_password variable with the application-specific password.

To solve the SMTPAuthenticationError issue with Google accounts, follow these steps:

Make sure you are using the correct username and password for the SMTP server. Double-check that you have entered the credentials correctly, including any uppercase or lowercase letters.

If you have 2-Step Verification enabled for your Google account, you cannot use your account password directly for SMTP authentication. Instead, you need to generate an application-specific password. Follow these steps to generate an application-specific password:

1.Go to the Google Account Security page.
2.Under the "Signing in to Google" section, click on "App Passwords".
3.If prompted, enter your Google account password.
4.Select "Mail" as the app and "Other (Custom name)" as the device.
5.Enter a custom name for the device (e.g., "Python Email Sender").
6.Click on the "Generate" button.
7.Google will generate an application-specific password for you.
8.Use this generated password in your Python script by replacing the smtp_password variable with the application-specific password.
9.After generating the application-specific password, update the smtp_password variable in your Python script with the new password.

Save the changes and run the script again. It should now be able to authenticate successfully with your Google account.

