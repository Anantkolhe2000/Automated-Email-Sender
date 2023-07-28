# Automated Email Sender

Automated Email Sender is a Java program designed to streamline the process of sending personalized emails to a large number of recipients. This project aims to save time and effort for users who need to send bulk emails with customized content based on recipient data.

## Features

- **Personalized Emails**: The program allows you to send personalized emails to recipients by incorporating their data into the email content.

- **Recipient Data**: The user can provide recipient data in the form of a CSV (Comma-Separated Values) file. The program will use this data to personalize each email.

- **Template Support**: You can create email templates with placeholders for recipient-specific information. The program will replace these placeholders with the actual data from the CSV file.

- **SMTP Configuration**: Users can set up their SMTP (Simple Mail Transfer Protocol) server settings to send emails through their preferred email service.

- **Attachments**: The program supports adding attachments to the emails.

## Installation

1. Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/your_username/automated-email-sender.git
```

2. Navigate to the project directory:

```bash
cd automated-email-sender
```

3. Open the project in your favorite Java IDE.

4. Make sure to resolve any dependencies by adding the required external libraries (if any).

## Usage

1. Prepare the CSV file with recipient data. The file should contain columns for recipient names, email addresses, and any other relevant data to be personalized in the email.

2. Update the email template with placeholders for the personalized data. For example, use `%NAME%` to represent the recipient's name.

3. Configure the SMTP server settings in the `config.properties` file. Provide the hostname, port number, and authentication credentials for your email service.

4. Run the program from your IDE or build it into an executable JAR file and run it using the command:

```bash
java -jar automated-email-sender.jar
```

5. Follow the on-screen instructions to select the CSV file, specify the email template, and send the personalized emails.

## Contributing

Contributions are welcome! If you have any ideas for improvements, bug fixes, or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Thanks to the developers of JavaMail and any other external libraries used in this project.

## Disclaimer

Please use this tool responsibly and only for sending emails to recipients who have given their consent to receive communications from you. Unauthorized use of this tool for spamming or other malicious purposes is strictly prohibited. The developers are not responsible for any misuse of this program.
