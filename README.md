 NLVX INSTA HUNTER 
An Advanced, Multi-Threaded tool for discovering Instagram accounts with a matching available Gmail address.NLVX INSTA HUNTER is a powerful script designed to find active Instagram usernames whose corresponding @gmail.com email address is available for registration. The tool uses advanced techniques to ensure high-speed, efficient discovery.
✨ Key Features
Feature
Description
🚀 High-Speed
Utilizes multi-threading to check thousands of accounts per minute.
🧠 Smart Speed Control
Automatically measures your internet speed and recommends the optimal performance setting.
✅ Dual Verification
First finds an active Instagram account, then verifies if the matching Gmail is available.
📊 Live Stats
Displays a real-time counter for Hits, Fails, and Not Found directly in your terminal.
💾 Saves Results
Automatically logs all successful hits to nlvxhints.txt with account details.
⚙️ How It Works
Instagram Search: The script sends requests to Instagram's API using random user IDs to find active accounts.
Smart Filtering: It ignores accounts with low follower counts to focus on more valuable usernames.
Gmail Check: For each username found (e.g., example ), the script checks if the email example@gmail.com is available.
Logging Hits: If the email is available, it's considered a "Hit," and the account details (username, followers, profile link) are saved to nlvxhints.txt.
📦 Installation & Usage
Follow these simple steps to get the tool running.
1. Prerequisites
Python 3.7+
pip (Python package installer)
2. Install Dependencies
First, clone the repository (or download the files). Then, open your terminal in the project folder and run the following command:
Bash
pip install requests user_agent cfonts colorama speedtest-cli
3. Run The Tool
To start the hunter, use the following command:
Bash
python your_script_name.py
Important Note: Upon running, the tool will prompt you to enter the number of threads and choose a speed level (1-4). A recommendation will be displayed based on your internet speed.
⚠️ Important Notes
❗️ Script Stopping Unexpectedly?
If the tool stops or encounters frequent errors, your IP address has likely been temporarily rate-limited. Using a VPN is the recommended solution to bypass this issue.
⚖️ Disclaimer
This tool is intended for educational and research purposes only. Any misuse for malicious or illegal activities is strictly prohibited. The developers assume no liability and are not responsible for any misuse or damage caused by this tool. Please respect the terms of service of the platforms you interact with.
