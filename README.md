# EVTX Session Auditor - Flask Web App

## Description
EVTX Session Auditor is a web-based application designed to analyze Windows Security Event Log (`.evtx` files) and extract meaningful logon and logoff session data. This project provides a modern interface to process EVTX logs, filter out service accounts, and display results in a structured table format with an option to download a CSV report.

This tool is an enhancement of the [LogonSessionAuditor](https://github.com/0xHasanM/LogonSessionAuditor) project, bringing a modern interface and additional filtering capabilities.

## Features
✅ Upload Windows Security EVTX log files for analysis <br>
✅ Filters out service accounts (usernames ending with `$`) <br>
✅ Parses logon (Event ID: 4624) and logoff (Event IDs: 4634, 4647) events <br>
✅ Displays results in a web-based table <br>
✅ Allows downloading the processed results as a CSV file <br>
✅ Automatically formats timestamps as `YYYY-MM-DD HH:MM:SS` <br>
✅ Standalone executable available (no need to run Python code) <br>

## Installation & Usage
### Download
Download the latest standalone executable from the [Releases Page](https://github.com/IRB0T/LogonSessionAuditor/releases/tag/LogonSessionAuditor) to get started.

### Prerequisites
- Windows OS

### Run the Application
Simply run the provided `LogonSessionAuditor.exe` file with Administrator Privileges. Once started, it will automatically open in your default browser.

## Contributing
Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

### Credits
This project is an extension of the [LogonSessionAuditor](https://github.com/0xHasanM/LogonSessionAuditor) created by **@0xHasanM**. A big thank you for the original work!

## License
This project is open-source and available under the **MIT License**.

