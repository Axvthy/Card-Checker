
# -- Card Reader & Logger 💳

The Credit Card Reader & Logger is a Python-based application that allows users to read data from a credit card's chip, securely log it,
and provide options for viewing and exporting the data. The app uses **AES-256** encryption to store sensitive card information and features automatic updates for easy software management.
The application is packaged as a **Windows executable (.exe)** with an installer for convenient distribution. Feel free to use this in any way as this is just a project of mine that I
wanted to do out of boredom.

This software is **NOT** intended for malicious activities such as: **Fraud, Scams etc.**

## -- 1. Overview 🔍

 - Card Data Reading: Reads credit card data via an Omnikey smart card reader.

 - AES-256 Encryption: Logs card data securely with encryption.

 - Decrypted Log Viewing: Allows users to view decrypted logs within the app.

 - Export Logs: Option to export decrypted logs to a .txt file.

 - Automatic Updates: The app checks for updates and downloads the latest version when available.

 ## -- 2. Installation 📁
 
-- Download the .exe installer file **(e.g., CreditCardReader_Setup.exe)**

-- Run the installer and follow the on-screen instructions to install the app

-- When you open the application, it will automatically check for updates from a server (e.g., GitHub).
   If a new version is available, the app will download and install the update automatically, ensuring you always have the latest version.

## -- 3. Usage Instructions 📜

 **Launch the Application**

**After installation, you can run the Credit Card Reader**

**Ensure that the Omnikey card reader is properly connected to your PC.**

**Insert a credit card into the reader.**

**Click the "Read Card & Log" button in the app.**

**The card data will be read and logged securely. The app will display the card's:**
 - **PAN (Primary Account Number)**
 - **Expiry Date**
 - **Cardholder Name**
 - **Remaining PIN Tries**

 
## -- 4. Viewing Decrypted Logs 📃

Click "View Decrypted Logs" to display logs that have been decrypted from the secure storage.

The logs will include:

- Card data (PAN, expiry, etc.)
- Timestamp of the scan
- Logs are displayed in a scrollable text box.

