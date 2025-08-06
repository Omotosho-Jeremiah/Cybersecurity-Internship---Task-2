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

## 🛡️ **Recommendations**  
- Never click links in unsolicited emails.  
- Report phishing emails to your IT team.  
- Use 2FA (two-factor authentication) for critical accounts.  

## ⁉ **Interview Questions (Brief Answers)**  
1. **What is phishing?**  
   A cyberattack where attackers impersonate legitimate entities to steal data.  
2. **How to verify sender authenticity?**  
   Check email headers for mismatches and use SPF/DKIM/DMARC tools.  
