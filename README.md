Phishing URL Scanner
A simple Python tool to detect suspicious and malicious URLs by combining heuristic checks with Google Safe Browsing API.

Features
Detects URLs using IP addresses instead of domain names
Flags suspicious top-level domains (TLDs) like .zip, .xyz, .tk, etc.
Checks for suspicious characters commonly used in phishing URLs
Warns if URL length is unusually long
Queries Google Safe Browsing API to check if the URL is known for malware, phishing, or unwanted software
Requirements
Python 3.x
requests library
python-dotenv library

