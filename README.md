# Digital-Forensics-Investigation-Lab-Acme-Bank
Digital Forensics Investigation Lab – Acme Bank University Assignment – Digital Forensic and Malware Analysis Comp 3012
Overview

This project documents a comprehensive digital forensic investigation conducted in response to the discovery of a keylogger on a staff PC at Acme Bank, a fictional UK bank. The investigation included covert evidence gathering, forensic acquisition, detailed analysis, and the reconstruction of events to identify suspects and understand the incident’s scope. The findings were compiled into a professional report outlining the investigative methodology, tools, and actionable insights to aid decision-making.
Objectives

    Conduct covert and overt forensic investigation phases

    Collect and preserve digital evidence maintaining chain of custody

    Analyse memory dumps, drive images, network traffic, and keylogger artifacts

    Correlate digital artifacts with physical evidence (CCTV, access logs)

    Identify suspects and reconstruct the timeline of keylogger deployment and data exfiltration

    Address operational trade-offs including resource allocation and cost

    Highlight limitations due to encryption and anti-forensic techniques

Methodology

The investigation followed a structured digital forensic process:

    Covert Independent Analysis – Reviewing network traffic, email servers, CCTV, HR reports to narrow suspect list

    Evidence Seizure and Preservation – Forensic imaging with write blockers, live memory capture, and documentation of the scene

    Examination and Analysis – Using specialized forensic tools to analyse memory, drives, and mobile devices

    Correlation and Reconstruction – Cross-referencing SYSTEM registry files, network logs, and physical evidence to identify suspects and timeline

    Reporting – Documenting procedures, findings, and recommendations for further action

Tools & Techniques

    Wireshark – Network traffic capture and analysis

    FTK Imager & FTK Toolkit – Forensic imaging and drive analysis

    Volatility – Memory dump analysis

    PRTK & John the Ripper – Password cracking tools

    TestDisk – Hidden partition and volume detection

    SQLite Database Reader – Extraction from mobile device databases

    Oxygen Forensics – Mobile device timeline reconstruction

    Faraday Bags & Write Blockers – Evidence preservation and transport

    WHOIS Lookup – Identifying ownership of malicious IP addresses

Key Findings

    Identification of a keylogger transmitting data at regular intervals to a malicious IP

    Creation of detailed suspect lists based on keylogger connection and network activity

    Reconstruction of the timeline correlating keylogger connection with CCTV and access logs

    Discovery of possible use of anti-forensic tools or keylogger development environments on suspect drives

    Challenges faced due to encryption and potential data deletion on SSDs

    Critical role of SYSTEM registry files and network analysis in suspect identification

This project was conducted as part of a university digital forensics module in a controlled lab environment. It does not represent a real-world investigation and was performed in compliance with ethical and legal standards.
