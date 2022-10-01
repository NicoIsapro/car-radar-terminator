# car-radar-terminator
CarRadarTerminator is an educative purpose and open source project with the goal of identifying cars with on-board radars.

This project is in a research stage, every help is welcome.

# Context

Since 2013, Car Radars have been allowed in France to be drove by 2 french policemens. They were still isolated, only 383 has been reported in 2017.
The problem came in 2018 when the state authorized **private companies** to drive these unmarked cars **by only one person** to do mass speed tracking at any hour in the day.

The cars are totally hidden in the mass of cars, the citizen driver can't recognize a car radar and the state is not buying only french cars anymore.

The only way to recognize a car before getting flashed is to recognize the plate.

# Main idea

A lot of cars plates have already been registered by a lot of different websites, the goal is to create a POC with OCR recognition connected to a mobile app. The OCR module will send data on plates to the mobile phone in real time and the mobile phone will query a database containing the identified cars radars plates. 
An alert will be sent to the user and he will be able to slow down.

Anoter functionality in the App will be to register a car radar plate, the system will work with community like Waze.

# Other ideas

The cars are working with a Windows OS on a tablet. The IHM is a web application. Even there is multiple possibilites of architecture, it is likely to think that the radar is an embedded system with even a WIFI connection to the tablet or that the radar system have a mobile connection and send live data to a cloud platform.

In both cases, it will be possible to identify the system some meters before passing in front of it.
