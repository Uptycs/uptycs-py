# uptycs-py
Uptycs API helper library (for Python 3)

This modules contains classes to interact with the Uptycs API using Python
Some commonly used classes include:
   UptApiAuth()     - Read an Uptycs API key file and create authorization header
   UptApiCall()     - Call an Uptycs API method
   UptAlertRule()   - Get or Create an alert rule
   UptAssets()      - Show/update assets registered in Uptycs, add/remove tags from assets
   UptEventRule()   - Get or Create an event rule
   UptLkpTable()    - Get or Create a lookup table (typically for whitelists/blacklists)
   UptQueryGlobal() - Run a query against global (flight recorder)
   UptQueryRt()     - Run a query against realtime
