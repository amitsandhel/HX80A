# HX80A
serial communication for the HX80A humidity probe by Omega

The code is written in Python 

humidity.py

Created by Amit Sandhel on May 12 2015  

This software script is able to run the api comands to run Omegas HX80A humidity sensor
this is a read only sensor with a built in temperature, humidity, relatively humidity and dewpoint values
all at once. 

Note: this script requires:
        1) Python 2.7
        2) PySerial (Python library that you will need to install separately via pip install)
        #http://pythonhosted.org/pyserial/
        3) Windows 7 Operating system
        
Note that the hardware manual for the machine is found in the manuals folder. an example of the output is found in the examples folder as a text file.  

#link to website of sensor 
https://www.omega.com/pptst/HX80A.html


# Instructions:
Open a Python 2.7 terminal can be a virtualenvironment if user wishes to do so. 
Run the following command "python humidity.py"

# TODO:
add capabilities for Linux 
