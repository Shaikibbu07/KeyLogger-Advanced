#🛡️ BlackTechX – Security Research Tool


 [![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://python.org)                                                        
 [![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Windows%20%7C%20macOS-orange.svg)](https://github.com/yourusername/BlackTechX-Spy-Tool)                                                         
 [![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)                                                   
 [![Status](https://img.shields.io/badge/Status-Development%20Ready-red.svg)](https://github.com/yourusername/BlackTechX-Spy-Tool)           

 > **⚠ WARNING: For Educational and Security Research Purposes Only**  


⚠️ Disclaimer

This project is developed strictly for educational purposes, cybersecurity learning, and authorized penetration testing.
Any unauthorized or malicious use is illegal.
The author is not responsible for misuse of this software.

📌 Overview

BlackTechX is a cross‑platform security research tool designed to help students and professionals understand how system‑level monitoring techniques work, enabling better defense strategies and security awareness.

📸 Features
Core Capabilities

Keystroke monitoring (educational analysis)

Automated screenshot capture

Webcam snapshot capture (if available)

Clipboard activity monitoring

System Intelligence

Hardware & software information

Network interface and IP details

File discovery by extension

Running process monitoring

Reporting

Email‑based compressed reports

Linux, Windows, macOS support

🚀 Installation & Usage
1️⃣ Clone the Repository
git clone https://github.com/yourusername/BlackTechX-Spy-Tool.git
cd BlackTechX-Spy-Tool

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Configure Email Reporting

Edit spy_tool.py:

EMAIL_CONFIG = {
    'smtp_server': 'smtp.gmail.com',
    'smtp_port': 587,
    'sender_email': 'your_email@gmail.com',
    'sender_password': 'your_app_password',  # Gmail App Password
    'recipient_email': 'recipient_email@gmail.com',
    'email_interval': 300
}

4️⃣ Run the Tool
python spy_tool.py

🔐 Gmail App Password Setup

Gmail requires an App Password for SMTP access.

Go to https://myaccount.google.com

Open Security

Enable 2‑Step Verification

Go to App passwords

Generate a password for Mail

Use the 16‑character password in the script

⚠️ Never commit real credentials to GitHub.

⚙ Configuration
ADVANCED_CONFIG = {
    'screenshot_interval': 60,
    'webcam_interval': 300,
    'clipboard_monitor': True,
    'email_interval': 300
}

file_extensions = ['.txt', '.doc', '.pdf', '.xls', '.csv', '.py', '.js']

search_directories = ['/home', '/Users']  # Linux/macOS
search_directories = ['C:\\', 'D:\\']      # Windows

🔧 System Requirements

Python 3.8+

Linux / Windows / macOS

Administrator privileges recommended

Linux Dependencies
sudo apt-get install gnome-screenshot scrot imagemagick python3-opencv

⚖ Legal & Ethical Use

✅ Educational learning
✅ Security research
✅ Authorized penetration testing

❌ Unauthorized surveillance
❌ Privacy violations
❌ Malicious usage

👤 Author

Ibrahim Shaik
Cybersecurity Student

GitHub: https://github.com/yourusername
