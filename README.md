# 🚀 LarpSense NFA Manager

**LarpSense NFA Manager** is a high-performance, elegantly designed tool built to make storing, managing, and switching between multiple Steam accounts instant and seamless.

## ✨ Features
* **Automated Login:** Streamlines the Steam authentication process using local `.vdf` configuration management and system registry integration for seamless session switching.
* **In-App Update Notifier:** Never miss a new release! The application automatically checks GitHub for the latest version and alerts you if an update is available.
* **System Tray Integration (Background Mode):** LarpSense doesn't clutter your taskbar. Close the app to minimize it to the System Tray (next to the Windows clock) where it silently runs in the background.
* **Quick Tray Login:** Right-click the hidden LarpSense icon in your taskbar, expand the **"Log In"** sub-menu, and select your account. The app instantly switches your active Steam session in the background without opening the main UI.
* **Custom Account Aliases:** Managing multiple accounts? Assign custom, neon-cyan labels (e.g., "Main", "Alt") to each account for easier identification. 
* **Smart Validation:** Automatically checks JWT tokens for expiration dates and valid formats before adding them to your library.
* **Join Our Community:** Built-in Discord integration! Click the Discord icon in the app to join our server, report bugs, and chat with the community.
* **DPAPI Support:** Safely manages and encrypts local Steam sessions utilizing Windows DPAPI infrastructure.
* **Cosmic UI:** An incredibly fast, hardware-accelerated dark mode interface built on Flet.

## 🗂️ How to use

### Option 1: Run from source (Recommended for developers)
1. Clone this repository: `git clone https://github.com/yourusername/LarpSense-NFA.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the application: `python main.py`

### Option 2: Standalone Executable
1. Download the latest release from the **Releases** tab.
2. Run the application.
3. Paste your Steam JWT token or account string to securely add it to your manager.
4. Click "Log In" on any card (or from the System Tray) to instantly switch accounts.

*Note on Windows SmartScreen: Because this is an open-source, independently developed tool, the compiled `.exe` does not hold a commercial Code Signing Certificate. As a result, Windows SmartScreen may display a "Windows protected your PC" prompt on the first launch. To proceed, click "More info" and then "Run anyway". All source code is fully transparent and available for review in this repository.*
