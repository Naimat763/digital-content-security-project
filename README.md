# Digital Content Security Project

## Overview
This project demonstrates how digital content can be protected using encryption and integrity techniques.

## Tools Used
- SHA-256 (Integrity checking)
- GPG (Encryption)
- OpenSSL (Optional encryption)

## Demo Steps

1. Create a file:
echo "This is secure content" > demo.txt

2. Generate hash:
sha256sum demo.txt

3. Modify file:
echo "modified" >> demo.txt

4. Generate hash again:
sha256sum demo.txt

5. Encrypt file:
gpg -c demo.txt

6. Decrypt file:
gpg demo.txt.gpg

## Purpose
To demonstrate how digital content can be secured and protected from unauthorized access.


## Author
Naimat Ullah

Please find my project repository below:

GitHub Link:
https://github.com/Naimat763/digital-content-security-project.git
LinkedIn link:
www.linkedin.com/in/naimat-ullah-cybersecurityv
