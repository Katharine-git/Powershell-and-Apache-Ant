Includes code that uninstalls and installs Apache Ant version 1.10 on checking the internet availability

The script contains 3 function ;

#1. To uninstall Apache Ant if it is already installed.
- Checks if Apache Ant already exists or not
- If yes, deletes the Ant folder

#2. Download and install the Apache Ant zip file if there is internet access.
- Checks for internet availability
- If yes, downloads the zip file , extract the file and install Apache Ant

#3. Download the zip file from a seperate location and install if no access to internet.
- For unavailability of internet access, extracts the zip file from a seperate location and install Apache Ant.


