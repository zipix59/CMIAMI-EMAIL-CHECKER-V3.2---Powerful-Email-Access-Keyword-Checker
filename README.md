📧 CMIAMI Email Checker V3.2 - Powerful Email Access & Keyword Search Tool
I'm thrilled to introduce CMIAMI Email Checker V3.2, a robust and versatile tool designed to validate email account access and perform targeted keyword searches within email content. Whether you're auditing accounts or researching specific topics, this tool offers a streamlined, secure, and customizable experience.

🚀 Features
Email Access Validation
Verifies email:password combinations using IMAP for reliable login checks.
Keyword Search
Searches email content for specific terms or phrases, with support for:
Predefined Categories:
Streaming (e.g., Netflix, HBO Max)
Cryptocurrency (e.g., Binance, Wallet, Bitcoin)
Trading/Finance (e.g., PayPal, Bank)
Hotels/Travel (e.g., Booking, Airbnb, Flight)
Shopping (e.g., Amazon, eBay, Order)
Social Media (e.g., Facebook, Instagram)
Gaming (e.g., Steam, Epic Games)
Custom Keywords: Define your own search terms for tailored results.
Broad Provider Support
Automatically detects and connects to IMAP servers for popular email providers, including Gmail, Outlook, Yahoo, and more.
Proxy Support
Enhances privacy with SOCKS4/SOCKS5 proxy integration.
Load proxies from a file (IP:Port format).
Scrape proxies directly from online sources.
SSL Verification Toggle
Option to enable or disable SSL certificate verification.
⚠️ Warning: Disabling SSL verification is insecure and may expose you to Man-in-the-Middle attacks. Use with caution and only if you fully understand the risks.
Detailed Output
Organizes results into categorized files:
Accounts with keyword matches.
Accounts that logged in successfully but had no keyword matches.
Accounts with login failures or errors.
Unique domains of successfully logged-in accounts.
Graceful Interruption Handling
Press Ctrl+C to safely save progress and exit without losing results.
User-Friendly Interface
Intuitive command-line menu for seamless navigation and operation.
📽️ Demo
Watch the tool in action: YouTube Demo

🛠️ Installation & Usage
Clone the repository:
bash

Copy
git clone https://github.com/<your-username>/CMIAMI-Email-Checker-V3.2.git
Install dependencies (if applicable, specify requirements, e.g., Python packages).
Configure your .env file with IMAP server details, email credentials, and proxy settings.
Run the tool:
bash

Copy
python cmiame_email_checker.py
Follow the command-line prompts to set up your email list, keywords, and proxy options.
📂 File Structure
results/keyword_hits.txt: Accounts with keyword matches.
results/success_no_keywords.txt: Successful logins without keyword matches.
results/failed_logins.txt: Failed login attempts or errors.
results/unique_domains.txt: Domains of successfully accessed accounts.
⚠️ Security Notice
Use Responsibly: This tool is intended for ethical and legal purposes, such as security research or account auditing with explicit permission.
SSL Risks: Disabling SSL verification is highly discouraged unless absolutely necessary, as it compromises security.
Proxy Safety: Ensure proxies are from trusted sources to avoid potential vulnerabilities.
🤝 Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Submit a pull request with a clear description of your changes.
Please adhere to the Code of Conduct and respect indentation rules (2 spaces, no tabs).

📜 License
This project is licensed under the GNU General Public License v3.0.

🌟 Acknowledgments
Inspired by the open-source security research community.
Thanks to contributors and testers for their valuable feedback.
🔗 Get Started
Ready to explore CMIAMI Email Checker V3.2? Clone the repo and start validating accounts or searching for keywords today! For issues or feature requests, please open a ticket in the Issues section.

Happy checking! 🚀

Notes for You:
GitHub Link: Replace <your-username> with your actual GitHub username and ensure the repository name matches your project.
Dependencies: If your tool requires specific libraries (e.g., Python's imaplib, socks), include a requirements.txt file or list them in the Installation section.
Code of Conduct & License: If you don’t have these files, consider adding a basic CODE_OF_CONDUCT.md and LICENSE file to your repository for professionalism.
YouTube Link: The provided link is embedded with a referral URL. I kept it as-is, but you may want to use a clean link (https://www.youtube.com/watch?v=8z9EjGr5-t8) for simplicity.
Ethical Disclaimer: I emphasized ethical use to align with GitHub's community standards and discourage misuse.
Formatting: Used GitHub Markdown headers, emojis, and code blocks for better readability and visual appeal.
Let me know if you want further tweaks, such as adding a specific section, changing the tone, or generating a visual (e.g., a logo or diagram) for the repo!
