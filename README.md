# Hash Cracking Lab Submission

## Overview
This repository contains the evidence and outputs for the MD5 hash cracking assignment using John the Ripper on Kali Linux.

## Tools Used
- John the Ripper (Jumbo version)
- Kali Linux
- rockyou.txt wordlist

## File/Folder Descriptions

### Evidence Screenshots (`evidence/screenshots/`)
- **installation.png** – Installed John the Ripper and wordlists, confirmed versions.
- **check_rawmd5.png** – Verified target hash format (raw-md5).
- **rockyou.png** – Confirmed wordlist presence and path.
- **password_cracked.png** – Cracked hash output showing plaintext password.




   john --format=raw-md5 --wordlist=/usr/share/wordlists/rockyou.txt hashes.txt
