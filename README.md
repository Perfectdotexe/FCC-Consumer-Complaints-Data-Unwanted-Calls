# FCC-Consumer-Complaints-Data-Unwanted-Calls
Raw data dumps from FCC Consumer Complaints Data - Unwanted Calls

"This data is for unwanted calls (telemarketing or robocalls). Individual informal consumer complaint data detailing complaints filed with the Consumer Help Center beginning October 31, 2014. This data represents information selected by the consumer. The FCC does not verify the facts alleged in these complaints." -FCC

Excel file that pulls the database from https://opendata.fcc.gov/Consumer/Consumer-Complaints-Data-Unwanted-Calls/vakf-fz8e (OData V4 Endpoint) every 60 minutes into a raw data Excel spreadsheet to be used to manipulate filtering to generate fresh lists of unwanted call phone numbers for call blocking using RPI software/hardware.

For those who are just looking for a generic list, please look at the master folder I have created a text file with a list of phone numbers which you can plug into your RPI call blocker software/hardware named fcc_phonelist.txt that has pre-populated phone numbers.

Please note, it's easier to allow list numbers than to deny list. To recompress the parted files into one individual file, please run the following command(s):

Windows:
copy /B input.z* output.zip

Linux:
cat input.z* > output.zip

Special thanks to:
@therefromhere on Stack Exchange for these commands.
