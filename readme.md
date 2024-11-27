# Email Sender Script

This Python script allows you to send emails securely using the **SMTP** protocol over SSL. It's a simple and efficient way to automate email-sending tasks.

---

## Features

- Sends emails using **SMTP over SSL** for secure communication.
- Allows customization of the sender, recipient(s), subject, and message body.
- Handles authentication via a username and password for the SMTP server.

---

## Prerequisites

1. **Python 3.x**: Ensure Python is installed on your system. You can download it from [python.org](https://www.python.org/).
2. **SMTP Server**: Obtain the SMTP server details and credentials from your email provider. For example:
   - SMTP Server: `smtp.att.yahoo.com`
   - Port: `465` (for SSL)

---

## Usage

### 1. Clone or Copy the Script
Save the script as `email_sender.py`.

### 2. Update the Script with Your Details
Replace the placeholders in the script with your actual email and SMTP server details:
- `SMTPserver`: Your email provider's SMTP server (e.g., `smtp.att.yahoo.com`).
- `sender`: Your email address.
- `destination`: The recipient's email address(es).
- `USERNAME` and `PASSWORD`: Your email credentials.

### 3. Run the Script
Execute the script in your terminal or command prompt:
```bash
python email_sender.py
