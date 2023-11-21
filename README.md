# PwrShl-IIS-CRT
This PowerShell script retrieves and organizes SSL certificate information for websites, allowing sorting and filtering based on user input for specific criteria like site name, binding information, and expiration dates.

# Website SSL Certificate Information Retrieval

This PowerShell script retrieves SSL certificate details for websites and provides sorting options based on various criteria.

## Features

- **Retrieve Details:** Gather SSL certificate information for websites.
- **Sort Options:** Sort retrieved data based on Site Name, Binding Information, Binding Name, Certificate Store, Certificate Name, and Expiration Date.
- **Filtering:** Filter results based on user-provided domains for specific searches.

## Requirements

- Windows environment with PowerShell installed.
- Appropriate permissions to access certificate stores.

## Usage

### Instructions

1. Run the script in a PowerShell environment.
2. Select an option:
    - `[1] Entire list`: Retrieve the complete SSL certificate information.
    - `[2] Search by Domain`: Enter a domain to filter results.
3. Choose a sorting option based on your criteria.
