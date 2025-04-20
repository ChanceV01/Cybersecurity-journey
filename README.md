(Starting Point)

## 🧠 Objective
Gain initial access and capture the user.txt flag.

## 🛠 Tools Used
- nmap
- SMB enumeration (enum4linux / smbclient)
- Hydra
- Metasploit

## 🔍 Summary
- Discovered open SMB share.
- Retrieved usernames and performed brute-force login.
- Gained access via Metasploit reverse shell.
- Found the user flag in `C:\Users\Administrator\Desktop\user.txt`.

## 🎯 Takeaways
- SMB is a common foothold on Windows machines.
- Credential reuse is powerful for initial access.
# 🐛 HTB - Oopsie (Starting Point)

## 🧠 Objective
Exploit a vulnerable web app and escalate privileges.

## 🛠 Tools Used
- nmap
- Gobuster
- Burp Suite
- Local privilege escalation (SUID binary)

## 🔍 Summary
- Found login panel, bypassed auth.
- Discovered `/upload.php` vulnerable endpoint.
- Uploaded reverse PHP shell.
- Escalated privileges using SUID `sudo` misconfig.

## 🎯 Takeaways
- Always check file upload features.
- Local privesc often relies on overlooked configs.
# 🧠 TryHackMe - Pre-Security Path Notes

## 🌐 Topics Covered
- Introduction to networking
- The web and HTTP/HTTPS basics
- Linux fundamentals
- Introduction to cybersecurity

## 🔑 Key Learnings
- Learned how IP addressing works.
- Practiced basic Linux navigation and commands.
- Understood common attack vectors.

## 📝 Favorite Rooms
- `Introduction to Networking`
- `Linux Fundamentals Part 2`
- `What is Cyber Security?`

## 🎯 Next Up
Start Complete Beginner path and OWASP Top 10.
# 🎓 Google Cybersecurity Certificate - Week 1 Notes

## 📚 Topics
- What is cybersecurity?
- Types of threats: phishing, malware, social engineering
- Roles in cybersecurity

## 💡 Concepts Learned
- CIA Triad (Confidentiality, Integrity, Availability)
- Cybersecurity domains: GRC, Network, SOC, IR

## 🎯 Notes
- Cybersecurity isn't just about hacking—it's also about defense and risk management.
- Consider building a home lab for hands-on practice.
touch certs/google-cybersecurity.pdf
touch certs/ibm-week1.pdf
git init
git remote add origin https://github.com/SpaceCowboy906/cybersecurity-learning.git
git add .
git commit -m "🚀 Initial commit with HTB, THM, Coursera progress"
git push -u origin main

