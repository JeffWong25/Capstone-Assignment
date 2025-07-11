# ICT30010 e-Forensic Fundamentals - Final Capstone Assignment
Investigator: Wong Jin Tao

Subject: Imanuel Leet-Hacker (aka Ima Hacker)

Date of Investigation: 28 June 2025

University: Swinburne University of Technology

# 📝 Project Overview
This repository contains the final capstone assignment for ICT30010: e-Forensic Fundamentals, where I performed a digital forensic investigation into a series of incidents linked to a suspect’s computer.

The assignment involved:

Verifying and analyzing a forensic image (ImaHacker.E01).

Using timeline evidence (timeline.csv) and multiple forensic tools.

Compiling a formal forensic report suitable for court use.

# 🔍 Investigation Summary
✔ Key Scenarios Investigated

Hackable.com.au Defacement (4 May 2010)

Found evidence of reconnaissance scans, user data theft, and defacement files.

Website Attack (4 March 2009, 2:22 AM)

Timeline analysis undermined suspect’s alibi through related activity before and after the alleged attack time.

Unauthorised Facebook Account Access (6 August 2010)

Discovered session hijacking with Firesheep, packet captures containing Facebook cookies, and crafted images uploaded to the victim’s account.

Collaboration via hidemyass.com Email

Extracted Outlook Express emails showing coordination and reporting of hacking activities to a collaborator at learntohack@hmamail.com.

# 🛠 Tools & Techniques Used
Kali Linux for forensic environment

EWF tools (ewfinfo, ewfverify, ewfmount) for handling .E01 image

The Sleuth Kit & Autopsy for partition analysis and timeline building

RegRipper to examine Windows registry (time zone & more)

Wireshark to analyze .pcap network captures

UnDBX to extract emails from .dbx files

Keyword searching, hash verification, and rigorous chain of custody throughout.

# 📑 Repository Contents
/report: PDF of final forensic report

/evidence: extracted key artifacts (emails, PCAPs, images) if allowed by assignment rules

# 🚀 Key Learnings
Maintaining strict chain of custody with MD5 verification.

Handling E01 forensic images and NTFS mounting with offset.

Creating forensic timelines in Autopsy and cross-referencing with Timescanner CSV.

Uncovering multi-scenario links through registry, filesystem, and network evidence.

Presenting findings in clear, non-technical language for court readiness.

# 📄 License & Disclaimer

This repository is purely for academic submission to Swinburne University of Technology.

Not intended for actual investigative or legal use outside this coursework.

