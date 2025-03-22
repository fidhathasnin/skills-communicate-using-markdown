# Introduction to Cybersecurity Basics
Cybersecurity refers to the practice of protecting systems, networks, and programs from digital attacks.
## What is Cybersecurity?
Cybersecurity refers to the practice of protecting systems, networks, and programs from digital attacks.
### Importance of Cybersecurity
- Protects sensitive data  
- Prevents unauthorized access  
- Safeguards digital infrastructure
### Cyber Attack Illustration

![Cyber Attack - A conceptual illustration depicting a digital cyber attack](https://github.com/fidhathasnin/skills-communicate-using-markdown/blob/main/3845387.jpg?raw=true)
#### Common Cyber Threats
1. Malware (Viruses, Worms, Ransomware)  
2. Phishing Attacks  
3. Distributed Denial-of-Service (DDoS)  

##### Cybersecurity Best Practices
- Use strong, unique passwords  
- Enable multi-factor authentication (MFA)  
- Regularly update software and systems


### Password Strength Checker (Python)

```python
def check_password_strength(password):
    if len(password) < 8:
        return "Weak: Password too short."
    elif not any(char.isdigit() for char in password):
        return "Weak: Add at least one number."
    elif not any(char.isupper() for char in password):
        return "Weak: Add at least one uppercase letter."
    else:
        return "Strong Password!"

password = input("Enter your password: ")
print(check_password_strength(password))




### 🛡️ Cybersecurity Task List

- [ ] Enable multi-factor authentication (MFA)
- [ ] Conduct vulnerability scans
- [ ] Set up a firewall for network security
- [ ] Perform regular data backups
- [ ] Monitor for suspicious activity
- [ ] Update security patches regularly
