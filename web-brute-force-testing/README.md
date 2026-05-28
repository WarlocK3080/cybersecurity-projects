## Web Application Brute Force Testing using Burp Suite

### Objective
To identify and analyze brute force vulnerabilities in a web application login system by intercepting and manipulating HTTP requests.

---

### Tools Used
- Burp Suite  
- DVWA (Damn Vulnerable Web Application)  
- Kali Linux  

---

### What I Did
- Intercepted login request using Burp Suite Proxy  
- Captured HTTP request containing login parameters  
- Sent the request to Burp Intruder for automated attack  
- Configured payload positions and attack type (Sniper)  
- Executed brute force attack using a password list  
- Analyzed server responses to identify successful login attempts  

---

### Key Findings
- The application was vulnerable to brute force attacks due to lack of protection mechanisms  
- Successful login attempts were identified through differences in response length  
- No rate limiting or account lockout was implemented  

---

### Conclusion
This project demonstrates how improper authentication mechanisms can expose web applications to brute force attacks. It highlights the importance of implementing protections such as rate limiting, CAPTCHA, and account lockout policies.
