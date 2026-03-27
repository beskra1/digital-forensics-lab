# digital-forensics-lab
Digital forensics lab involving hidden volume discovery, file extraction, and analysis
# Digital Forensics & File Recovery Lab

## Objective
Identify, recover, and securely transfer hidden or suspicious files from a system while preserving file integrity.

## Scenario
A hidden storage volume was suspected to contain unauthorized or suspicious files. The objective was to locate the volume, identify any anomalous files based on timestamps, and securely extract them for further analysis without modifying the original data.

## Process Overview
- Identified hidden volume using Disk Management when it was not visible in File Explorer  
- Assigned a drive letter to restore access to the hidden storage  
- Reviewed file metadata (creation and modification dates) to identify anomalies  
- Isolated suspicious files based on deviation from expected timeline  
- Securely transferred files using SCP to a separate analysis system  
- Archived evidence into a .tar file to preserve integrity  
- Performed static analysis on a PDF using `pdfid` and recorded findings  

## Tools & Technologies
- Windows Disk Management  
- PowerShell / Command Line  
- SCP (Secure Copy Protocol)  
- File Explorer  
- PDF analysis tool (`pdfid`)  

## Outcome
Successfully located hidden data, identified suspicious files based on metadata analysis, preserved evidence integrity during transfer, and completed initial forensic analysis.

## Key Takeaways
- Importance of validating storage devices beyond standard user visibility  
- Maintaining chain of custody and data integrity during forensic handling  
- Using structured methodology to identify and isolate anomalies  
- Gained practical exposure to digital forensics and basic incident response workflows

This lab was completed in a controlled environment as part of cybersecurity coursework. Focus was placed on maintaining data integrity and following a structured forensic workflow.
