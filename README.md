# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
<img width="1898" height="955" alt="436824504-f59bf54d-2fe1-4e89-8647-87e4f961686f" src="https://github.com/user-attachments/assets/550b1b99-d002-45e0-a321-c2028ad59b3a" />

![WhatsApp Image 2025-09-20 at 14 37 15 (1)](https://github.com/user-attachments/assets/f04be898-5bc3-4116-bac2-a5ce39092210)
![WhatsApp Image 2025-09-20 at 14 37 15 (2)](https://github.com/user-attachments/assets/568085e9-89be-4fac-85b1-c72e26d373a1)
![WhatsApp Image 2025-09-20 at 14 37 15](https://github.com/user-attachments/assets/1fc01426-4a35-4968-a77b-03153b331ba6)
![WhatsApp Image 2025-09-20 at 14 37 18](https://github.com/user-attachments/assets/9d0765d6-477f-49cd-8129-1e3de4a8e606)


<img width="1914" height="930" alt="3 6" src="https://github.com/user-attachments/assets/0410bcf7-809b-4e94-952e-26f7baa2f053" />
<img width="887" height="473" alt="Screenshot 2025-09-20 at 8 52 50 PM" src="https://github.com/user-attachments/assets/94d8a5a6-2346-4001-9267-60e5f0569529" />
<img width="1917" height="874" alt="3 7" src="https://github.com/user-attachments/assets/aee6d822-9368-4012-b049-7db8cd87ef2d" />


## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
