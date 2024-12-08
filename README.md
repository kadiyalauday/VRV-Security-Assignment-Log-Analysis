# VRV-Security-Assignment-Log-Analysis
In this assignment, I developed a Python script to extract, analyze, and report key insights from a sample log file. The script employs regular expressions for parsing log entries and uses the pandas library for data manipulation and analysis. Below is a summary of the key functionalities:

*Log Data Extraction:*

- Extracted details such as IP addresses, timestamps, HTTP methods, endpoints, protocols, status codes, and response sizes using regular expressions.
  
*Data Transformation:*

- Organized the extracted data into a structured pandas DataFrame.
- Added a custom message column to classify log entries based on status codes (e.g., "Valid" for successful requests and "Invalid Credentials" for failed ones).

*Analysis:*

- Counted the number of requests made by each IP address.
- Identified the most frequently accessed endpoints.
- Detected suspicious activities, such as failed login attempts (status code 401), and flagged IP addresses associated with these events.
  
*Results Export:*

- Exported the analysis results to an Excel file with multiple sheets for better organization:
   - Requests per IP address.
   - Most accessed endpoints.
   - Suspicious activities.
