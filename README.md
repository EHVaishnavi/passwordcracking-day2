# Hash Cracking Lab Submission

## Overview
This repository contains the evidence and outputs for the MD5 hash cracking assignment using John the Ripper on Kali Linux.

## Tools Used
- John the Ripper (Jumbo version)
- Kali Linux
- rockyou.txt wordlist

## File/Folder Descriptions

Johntheripper_installation.png: Installation of John the Ripper on Kali Linux.

htr_passwordcracked.png: Output showing the cracked password.

jtr_testing_rawmd5.png: Testing the raw MD5 hash format.

rockyou_wordlist.png: Verifying the presence of the rockyou.txt wordlist.




   john --format=raw-md5 --wordlist=/usr/share/wordlists/rockyou.txt hashes.txt
