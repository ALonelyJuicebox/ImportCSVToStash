<h1 align="center">Import CSV to Stash Powershell Script</h1>
<p align="center"><img src="/readme_assets/header.png" ></p>

**Import CSV to Stash** is an automated CSV import tool for Stash, written in Powershell.

It's designed to work specifically with [the JDownloader2 script I wrote](https://github.com/ALonelyJuicebox/JD2_WriteInfoCSV) for generating CSV files from downloaded URLs.

* Simple to use with a straightforward command line based UI!
* Great way to get URLs into your Stash!
* Filesize + Filename match requirements make this tool incredibly safe on your Stash database
  


## 🍦 How it Works
- This script iterates through a defined folder and parses CSV files.
-  If the parsed CSV file contains a file in your Stash, the script will check to see if your scene has a matching URL. If the scene doesn't have that URL, it'll add what's in the CSV file.

## 💻 Requirements
- Stash v0.25.1 ([Released 2024-3-12](https://github.com/stashapp/stash/releases/))
- Any major operating system (Windows/macOS/Linux) running [Microsoft Powershell](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell?view=powershell-7.3)


## 📖 How to Run

1. Ensure the latest version of [Microsoft Powershell](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell?view=powershell-7.3) is installed. 
2. Open a Powershell prompt in the same directory as the script and run the command `.\importcsvtostash.ps1`
3. The script will then ask you where your csv files are located
