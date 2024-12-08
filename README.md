# VRV-Security-Assignment-Log-Analysis
In this assignment, I developed a Python script to extract, analyze, and report key insights from a sample log file. The script employs regular expressions for parsing log entries and uses the pandas library for data manipulation and analysis.

Below is a summary of the key functionalities:
- Extracted details such as IP addresses, endpoints, and status codes using regular expressions.
- Added a custom message column to classify log entries based on status codes (e.g., "Valid" for successful requests and "Invalid Credentials" for failed ones).
- Organized the extracted data into a structured pandas DataFrame.
- Counted the number of requests made by each IP address.
- Identified the most frequently accessed endpoints.
- Detected suspicious activities, such as failed login attempts (status code 401), and flagged IP addresses associated with these events.
- Exported the analysis results to an Excel file with multiple sheets for better organization
