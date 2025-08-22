# Email-Sending-App-Node.js-Nodemailer-Gmail-
Email Sending App (Node.js, Nodemailer, Gmail) – A simple Node.js application to send automated emails using Nodemailer and Gmail SMTP. Configured with Google App Passwords for secure authentication, it allows customizable subject, body (text/HTML), and recipients, with support for attachments.

# 📧 Email Sending App (Node.js, Nodemailer, Gmail)

A simple Node.js application to send automated emails using **Nodemailer** and **Gmail SMTP**.  
This app supports sending plain text, HTML emails, and attachments with secure authentication using **Google App Passwords**.

---

## 🚀 Features
- Send emails via Gmail SMTP using **Nodemailer**  
- Secure login with **Google App Passwords**  
- Customizable **subject, body, and recipients**  
- Supports **plain text & HTML content**  
- Send **attachments** (e.g., files, reports)  

---

## 📂 Project Structure
email-app/
├── index.js
└── package.json

yaml
Copy code

---

## ⚙️ Installation & Setup

1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-username/email-app.git
   cd email-app
Install dependencies:

bash
Copy code
npm install
Configure your Gmail:

Enable 2-Step Verification in Google Account

Generate an App Password for Gmail

Replace credentials in index.js:

js
Copy code
const EMAIL_USER = "your_email@gmail.com";
const EMAIL_PASS = "your_app_password";
Run the app:

bash
Copy code
npm start
📧 Example Email
To: recipient@example.com

Subject: Test Email from Node.js App 🚀

Body:

Plain text: Hello! This is a test email.

HTML: <h2>Hello!</h2><p>This is a <b>test email</b> 🚀</p>

Attachment: sample.txt

🛠 Dependencies
Node.js

