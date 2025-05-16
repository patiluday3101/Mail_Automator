# Mail_Automator
# 📧 Updated Mail Automation

Automate your email workflows securely and efficiently. This project streamlines the process of fetching, formatting, and delivering utility bills through email and WhatsApp, making it perfect for businesses, utility providers, or personal use.

## 🚀 Features

* Secure Database Connection (PostgreSQL)
* Automated Bill PDF Download and Delivery
* Bulk Email and WhatsApp Notification Support
* Error Logging and Retry Logic
* Environment Variable Management for Enhanced Security

## 🛠️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/mail-automation.git
cd mail-automation
```

2. **Set up environment variables:**
   Create a `.env` file in the project root:

```
POSTGRE_HOST=your-postgre-host
POSTGRE_DATABASE=your-database-name
POSTGRE_USER=your-database-user
POSTGRE_PASSWORD=your-database-password
POSTGRE_PORT=5432
SMTP_SERVER=smtp.your-email-provider.com
SMTP_PORT=587
SENDER_EMAIL=your-email@example.com
SENDER_PASSWORD=your-email-password
WHATSAPP_API_URL=https://graph.facebook.com/v15.0/<PHONE_NUMBER_ID>/messages
WHATSAPP_TOKEN=your-whatsapp-token
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

## 📄 Usage

Run the main script to start sending emails and WhatsApp messages:

```bash
python main.py
```

Customize your Excel files and recipient lists as needed. Check the code for more advanced options.

## 📂 Project Structure

```
mail-automation/
├── main.py        # Main script to send emails
├── utils.py       # Utility functions
├── .env           # Environment variables
├── requirements.txt # Python dependencies
└── README.md      # Project documentation
```

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🌐 Connect

Feel free to connect with me on [LinkedIn](https://linkedin.com/in/your-profile) or follow me on [GitHub](https://github.com/your-username)!

Happy Automating! 🚀
