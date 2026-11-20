PDF Password Recovery – Capture The Flag (CTF)

Project Overview

This project documents a hands-on Capture The Flag (CTF) exercise completed as part of my cybersecurity learning journey with Networkwalks.

The challenge involved recovering passwords from encrypted PDF documents using hash extraction techniques and dictionary-based password attacks.

I explored two password-recovery workflows and compared their results using Networkwalks tools and John the Ripper (Johnny).

  Objectives

- Extract password hashes from encrypted PDF documents.
- Perform dictionary-based password attacks.
- Practice using password-auditing tools.
- Compare two password-recovery approaches.
- Understand the limitations of dictionary attacks.

  Tools Used

Tool| Purpose
Networkwalks Hash Calculator| PDF hash extraction
Networkwalks Password Cracker| Dictionary attacks
OnlineHashCrack PDF Hash Extractor| PDF hash extraction
Johnny (John the Ripper GUI)| Password auditing and recovery
Text Editor| Preparing extracted hashes

  Methodology

Workflow 1: Networkwalks Tools

1. Uploaded an encrypted PDF to the Networkwalks Hash Calculator.
2. Extracted the corresponding hash string.
3. Submitted the hash to the Networkwalks Password Cracker.
4. Performed a dictionary attack.
5. Recorded the recovery results.

Workflow 2: OnlineHashCrack and Johnny

1. Uploaded an encrypted PDF to the OnlineHashCrack PDF Hash Extractor.
2. Extracted the PDF hash string.
3. Saved the extracted hash in a text document.
4. Opened Johnny (John the Ripper GUI).
5. Uploaded the text document containing the hash.
6. Executed the password-cracking process.
7. Verified the recovered password.

  Results and Observations

Three PDF documents were documented using both workflows.

PDF| Networkwalks Password Cracker| Johnny
PDF 1| Unsuccessful| Successful
PDF 2| Successful| Successful
PDF 3| Successful| Successful

Key Observations

- Johnny successfully recovered the passwords for all three documented PDFs.
- The Networkwalks Password Cracker recovered two passwords but was unsuccessful with PDF 1.
- The unsuccessful attempt indicated that additional dictionary lists were required.

This exercise demonstrated how dictionary coverage can affect password-recovery results.

  Key Learning Outcomes

- PDF password hash extraction.
- Hash handling and text-file preparation.
- Dictionary-based password attacks.
- Practical use of John the Ripper through Johnny.
- Comparing password-recovery tools.
- Understanding wordlist limitations.
- Troubleshooting unsuccessful recovery attempts.

  Evidence

Screenshots documenting the hash extraction process, password-auditing workflow, and challenge completion are included in the "screenshots/" directory.

Sensitive information, including recovered passwords, hash strings, and CTF flags, has been redacted from publicly shared evidence.

⚠️ Disclaimer

This exercise was conducted as part of an authorized cybersecurity learning activity for educational purposes.
