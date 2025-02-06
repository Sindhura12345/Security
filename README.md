# Information Security

**VirusTotal Domain Reputation Checker**

This automation script processes a list of domain names from an Excel (.xlsx) file and checks their reputation using the VirusTotal API. It then generates an output file categorizing domains as malicious, suspicious, clean, or undetected.

**Features**

✅ Reads domain names from an input .xlsx file
✅ Uses VirusTotal API to fetch domain reputation data
✅ Outputs results in a structured format
✅ Categorizes domains based on malicious, suspicious, clean, and undetected statuses
✅ Saves results in an output .xlsx file

**Requirements**

Make sure you have the following installed before running the script:

Python 3.x
pandas for handling Excel files
openpyxl for working with .xlsx files
requests for making API calls


**Output** ::
The script generates an output file (output.xlsx) with the following columns:
Domain
Malicious
Suspicious
Clean
Undetected
