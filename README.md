# 🛡️ Cybersecurity Internship – Task 2: Phishing Email Analysis

🔍 **Objective**  
To analyze a suspicious email and identify phishing indicators using manual inspection and threat intelligence tools.

🛠 **Tools Used**  
- VirusTotal  
- Manual Header/Body Analysis  

📧 **Sample Email Details**  
**From:** security-alert@paypai.com  
**Subject:** [URGENT] Your PayPal Account Is Suspended!  
**Link:** http://paypal-login-secure.com

📊 **Phishing Indicators Found**

📌 **Spoofed Sender Domain**  
- `paypai.com` ≠ `paypal.com`  
- **Type:** Email Spoofing

📌 **Suspicious URL**  
- Misleading domain that mimics PayPal login page  
- Detected by manual analysis, undetected in VirusTotal

📌 **Urgent Language**  
- "Verify immediately", "account will be closed"  
- **Type:** Social Engineering

📌 **Unnatural Tone**  
- Robotic and threatening language typical of phishing campaigns

⚠️ **Risk Analysis**  
- URL could lead to credential theft if clicked  
- Domain mimics a popular brand, increasing the chance of user error

✅ **Recommendations**  
- Train users to recognize fake domains and urgency tactics  
- Report phishing emails to IT/security team immediately  
- Use email filters and domain validation (SPF, DKIM, DMARC)

📁 **Files in Repo**  
- phishing_sample.txt: Simulated phishing email  
- README.md: Task summary and phishing analysis
