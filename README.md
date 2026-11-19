# NETWORKWALKS-B084-2YU-WK3-PM1-CYBERSECURITY-LAB-SETUP
Hands-on lab recovering a password-protected PDF’s password using John the Ripper (John &amp; Johnny) and Networkwalks’ online Hash Calculator &amp; Password Cracker — demonstrating password hash extraction, cracking, and the importance of strong passwords.

# PDF Password Cracking Lab — JTR (John & Johnny) and Networkwalks Hash Tools

## Overview
This repository documents a hands-on lab exercise exploring password recovery
techniques on a password-protected PDF file. The goal was to understand how
password hashing and cracking work, and why weak passwords are a security risk.

Two approaches were used:
1. **John the Ripper (JTR)** and its GUI front-end **Johnny**, run locally on Windows.
2. **Networkwalks Hash Calculator** and **Password Cracker**, browser-based tools
   that extract and crack a PDF hash without local installation.

This was completed as part of a cybersecurity internship at Networkwalks IT
Solutions & Training (Oct–Nov 2026).

## Disclaimer
This lab was performed on a test file (`My Locked PDF1.pdf`) created solely for
this exercise. The techniques here are intended for authorized security testing,
education, and awareness of password strength — not for accessing files or
systems without permission.

## Key Takeaways
- Password hashes can be extracted from protected PDF/ZIP/Office files and tested
  offline against wordlists.
- Short, common, or dictionary-based passwords are cracked quickly; longer,
  random passphrases resist cracking far better.
- GUI tools (Johnny) lower the barrier to entry but rely on the same underlying
  engine as the John CLI.
- Browser-based cracking tools are convenient for quick lab demonstrations but
  are not suited for sensitive or production hashes, since the file is uploaded
  to a third party.

## Tools Used
- [John the Ripper](https://www.openwall.com/john/)
- Johnny (JTR GUI)
- Networkwalks Hash Calculator & Password Cracker (web-based)

## Author
Roopa — Cybersecurity Intern, Networkwalks IT Solutions & Training
