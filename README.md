 Identify phishing characteristics in a suspicious email sample.
 Phishing Email Analysis Report  
🔍 Email Sample Source 
- Downloaded from: [GitHub phishing samples](https://www.phishing.org/phishing-examples)  

🚩 Phishing Indicators Found
1. **Spoofed Sender:** `support@amaz0n-security.com` (fake Amazon domain).  
2. **Mismatched Links:**  
   - Displayed: `https://amazon.com/reset-password`  
   - Actual: `http://malicious-site.com/login`  
3. **Urgent Language:**  
   - *"Your account will be suspended in 24 hours!"*  
4. **Grammar Errors:**  
   - *"Dear Costumer, youre account has bin locked."*  
5. **Suspicious Headers:**  
   - `Return-Path: <bounces@phishing-server.com>` (doesn’t match "From").
6.  **Tools & Resources**
    *Email Header Analyzers:*
   - Google Admin Toolbox  `https://toolbox.googleapps.com/apps/messageheader/analyzeheader`
   - MXToolbox  `https://mxtoolbox.com/EmailHeaders.aspx`

## 🛡️ **Recommendations**  
- Never click links in unsolicited emails.  
- Report phishing emails to your IT team.  
- Use 2FA (two-factor authentication) for critical accounts.  

## ⁉ **Interview Questions (Answers)**  🔍💡
### **1. What is phishing?**  
Phishing is a cyberattack where attackers impersonate legitimate entities (e.g., banks, companies) via emails, messages, or websites to trick victims into revealing sensitive information (passwords, credit card numbers) or downloading malware.  

**Example:**  
> *"You’ve won a prize! Click here to claim it."* (Leads to a fake login page.)  

### **2. How to identify a phishing email?**  
- **Suspicious sender address:** Misspelled domain (e.g., `support@amaz0n.com`).  
- **Urgent/threatening language:** *"Your account will be suspended in 24 hours!"*  
- **Mismatched links:** Hover to see the actual URL (e.g., `http://malicious-site.com` disguised as `https://paypal.com`).  
- **Poor grammar/spelling:** *"Dear Costumer, youre account is compromised."*  
- **Unexpected attachments:** `.exe`, `.zip`, or `.docm` files.  

### **3. What is email spoofing?**  
Email spoofing is forging the "From" address to make an email appear sent by a trusted source (e.g., `CEO@yourcompany.com`). Attackers exploit protocols (SMTP) that lack sender verification.  

**How it works:**  
- The email header shows `From: support@apple.com`, but the actual sender is `attacker@phishing.com`.  


### **4. Why are phishing emails dangerous?**  
- **Data theft:** Steals login credentials, credit card details.  
- **Malware infection:** Ransomware, spyware via attachments/links.  
- **Financial loss:** Fraudulent transactions.  
- **Reputation damage:** If attackers impersonate your organization.  

**Stat:** 36% of data breaches involve phishing ([Verizon DBIR 2023](https://www.verizon.com/business/resources/reports/dbir/)).  


### **5. How can you verify the sender’s authenticity?**  
- **Check email headers:** Look for mismatches between `From`, `Return-Path`, and `Received-SPF` fields.  
- **SPF/DKIM/DMARC:** Use tools like [MXToolbox](https://mxtoolbox.com/EmailHeaders.aspx) to validate these records.  
- **Contact the sender:** Use a known phone number/website (not from the email).  


### **6. What tools can analyze email headers?**  
- **Free online analyzers:**  
  - [Google Admin Toolbox](https://toolbox.googleapps.com/apps/messageheader/)  
  - [MXToolbox](https://mxtoolbox.com/EmailHeaders.aspx)  
- **Email clients:** Outlook (View → Message Details), Gmail (Show Original).


### **7. What actions should be taken on suspected phishing emails?**  
1. **Do NOT** click links/download attachments.  
2. **Report it:** Forward to your IT team or `reportphishing@apwg.org`.  
3. **Delete it** after reporting.  
4. **Scan your device** for malware if you interacted with the email.  


### **8. How do attackers use social engineering in phishing?**  
Attackers exploit human psychology to bypass technical defenses:  
- **Authority:** Impersonating CEOs ("Urgent wire transfer needed").  
- **Scarcity:** *"Limited-time offer! Claim now!"*  
- **Fear:** *"Your account is hacked! Click to secure it."*  
- **Familiarity:** Mimicking trusted brands (e.g., PayPal, Microsoft).  

**Example:**  
> *"Hi [Your Name], your Netflix subscription expired. Update payment details here."*  

   
