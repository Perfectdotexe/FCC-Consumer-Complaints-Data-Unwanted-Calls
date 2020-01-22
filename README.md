# FCC-Consumer-Complaints-Data-Unwanted-Calls
Raw data dumps from FCC Consumer Complaints Data - Unwanted Calls

Excel file that pulls the database from https://opendata.fcc.gov/Consumer/Consumer-Complaints-Data-Unwanted-Calls/vakf-fz8e (OData V4 Endpoint) every 60 minutes into a raw data Excel spreadsheet to be used to manipulate filtering to generate fresh lists of unwanted call phone numbers for call blocking using RPI software/hardware.

For those looking for a generic list please refer to phone_fcc.txt I have created a generic list that I have uploaded for it to plugged into your RPI call blocking software/hardware.

Please note, it's easier to whitelist numbers than to blacklist. To recompress the parted files into one individual file, please run the following command(s):

Windows:
copy /B input.z* output.zip

Linux:
cat input.z* > output.zip

Special thanks to:
@therefromhere on Stack Exchange for these commands.
