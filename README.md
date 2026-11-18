# Week 3 – Password Cracking

A hands-on cybersecurity learning project exploring password recovery from a password-protected PDF using two different approaches:

1. **John the Ripper (JTR) and Johnny GUI**
2. **NetworkWalks Hash Calculator and Password Cracker**

The exercises were completed in a controlled learning environment for educational purposes.

> **Important:** Only perform password-security testing on files and systems you own or have explicit permission to test. Do not use these techniques against other people's accounts, files, or systems.

## Project objectives

- Understand the basic role of password hashes in password-protected files.
- Extract a PDF password hash using the tools provided in each lab.
- Run a password-recovery exercise using two different toolsets.
- Observe how password complexity can affect the time required to recover a password.
- Understand why strong, unique passwords are important.

## Module 1: Password Cracking with John the Ripper

**Tools used**
- John the Ripper
- Johnny (graphical interface)
- PDF hash extraction tool
- Windows PC

**High-level workflow**
1. Prepare the password-protected PDF supplied for the lab.
2. Extract the PDF hash.
3. Save the hash in a text file.
4. Load the hash into Johnny.
5. Start the password-recovery process.
6. Verify the recovered password by opening the lab PDF.

### Evidence – Module 1


<img width="950" height="414" alt="Step 1" src="https://github.com/user-attachments/assets/02351d53-c240-4a71-9bc5-d9de8fb1b963" />
<img width="959" height="539" alt="Step 2" src="https://github.com/user-attachments/assets/68040692-82e6-439a-89f5-c12b8b917b7b" />
<img width="959" height="539" alt="Step 3" src="https://github.com/user-attachments/assets/96e6ac80-bf4a-4ac5-a366-c848c179de70" />
<img width="959" height="539" alt="Step 4" src="https://github.com/user-attachments/assets/3dd5c5f1-7067-4eb6-a6e6-14b6fdcf425b" />
<img width="959" height="539" alt="Step 5" src="https://github.com/user-attachments/assets/fa75eb41-986d-4340-8ac0-ccbf38b78ca5" />

Suggested evidence:
- [ ] Hash extraction result
- [ ] Hash loaded in Johnny
- [ ] Password-recovery result
- [ ] Successfully opened test PDF

<!-- Add screenshots to the folder above. You can also embed them here, for example:
![John the Ripper result](evidence/module-1-john-the-ripper/jtr-result.png)
-->

## Module 2: Password Cracking with NetworkWalks Tools

**Tools used**
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker
- Web browser
- Windows PC or Kali Linux

**High-level workflow**
1. Prepare the password-protected PDF supplied for the lab.
2. Use the Hash Calculator to extract the PDF hash.
3. Copy the complete hash value.
4. Submit the hash to the Password Cracker.
5. Run the recovery process.
6. Verify the recovered password by opening the lab PDF.

### Evidence – Module 2

<img width="937" height="413" alt="Step 1" src="https://github.com/user-attachments/assets/474bfd46-308b-480e-b6f9-fa98d72f1db4" />

https://github.com/user-attachments/assets/8cada376-a3e3-4021-b66b-a339e23ffa8b

<img width="950" height="421" alt="Step 3" src="https://github.com/user-attachments/assets/57b3a062-7b52-4ed7-9511-17b98dbe472e" />



Suggested evidence:
- [ ] Hash Calculator result
- [ ] Hash submitted to Password Cracker
- [ ] Password-recovery result
- [ ] Successfully opened test PDF

<!-- Add screenshots to the folder above, for example:
![NetworkWalks result](evidence/module-2-networkwalks-tools/networkwalks-result.png)
-->

## Key learning outcomes

- Gained practical exposure to password-hash extraction and recovery workflows.
- Used both a command-line-based password auditing tool with a GUI front end and browser-based tools.
- Compared two approaches to the same controlled lab exercise.
- Reinforced the importance of long, unique passwords and good password practices.

## Repository structure

```text
week3-password-cracking/
├── README.md
├── .gitignore
└── evidence/
    ├── module-1-john-the-ripper/
    │   └── .gitkeep
    └── module-2-networkwalks-tools/
        └── .gitkeep
```

## Disclaimer

This repository documents an educational lab exercise. It is not intended to encourage unauthorised access. Any testing should be performed only in an authorised environment using files and systems for which you have permission.
