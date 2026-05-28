## Password Security Analysis using Linux & John the Ripper

### Objective
To analyze how weak passwords can be compromised using brute force and dictionary attacks, and how strong password policies act as a defense mechanism.

---

### Tools Used
- Kali Linux  
- John the Ripper  
- RockYou Wordlist  
- Linux Commands (`useradd`, `passwd`, `unshadow`)  

---

### What I Did
- Created user accounts in a Linux environment  
- Assigned weak passwords to simulate insecure configurations  
- Extracted password hashes using `unshadow`  
- Performed offline password cracking using John the Ripper  
- Re-tested the system using strong password policies  

---

### Key Findings
- Weak numeric passwords were cracked quickly using dictionary attacks  
- Password hashes can be exploited if exposed  
- Strong passwords significantly reduced the success of brute force attacks  

---

### Conclusion
This project demonstrates the importance of strong password policies and secure handling of password hashes. It highlights how weak credentials can be easily compromised and how proper security practices can mitigate such risks.
