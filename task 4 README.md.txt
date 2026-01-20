# Cyber Security Internship – Task 4
## Password Security & Authentication Analysis

## Objective
To understand how passwords are stored, how weak passwords are attacked, and how strong authentication mechanisms protect user accounts.

## Password Storage
Passwords are not stored in plain text. Instead, they are stored using hashing techniques that convert passwords into fixed-length, irreversible values.

## Hashing vs Encryption
Hashing is a one-way process and cannot be reversed, whereas encryption is a two-way process where data can be decrypted using a key. Hashing is preferred for password storage.

## Common Hash Types
- MD5 (weak and outdated)
- SHA-1 (weak and insecure)
- bcrypt (strong and recommended)

## Password Attacks

### Brute Force Attack
In a brute force attack, all possible password combinations are tried until the correct one is found. This method is slow but guaranteed to work on weak passwords.

### Dictionary Attack
In a dictionary attack, commonly used passwords from a wordlist are tried. This attack is faster and effective against simple passwords.

## Why Weak Passwords Fail
Weak passwords are short, predictable, and often based on common words. Such passwords can be cracked within seconds using dictionary or brute force attacks.

## Multi-Factor Authentication (MFA)
MFA adds an extra layer of security by requiring additional verification such as OTPs or authenticator apps. Even if a password is compromised, MFA prevents unauthorized access.

## Recommendations for Strong Authentication
- Use long passwords with mixed characters
- Avoid common words and patterns
- Use unique passwords for each account
- Enable Multi-Factor Authentication
- Prefer strong hashing algorithms like bcrypt

## Conclusion
This task highlights the importance of strong passwords and multi-factor authentication in protecting systems from unauthorized access.
