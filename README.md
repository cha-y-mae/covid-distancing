# COVID-19 Social Distancing device

## About

This project was developed with two of my classmates for the Computer Programing for Engineers class. 

## Description

To break the chain of transmission through enforcing COVID-19 physical distancing protocols, we have designed a wearable device to help you maintain a safe distance and protect yourself and the community from COVID-19. Its primary advantages are its simple and intuitive user interface and its confidentiality - it respects the user's privacy and does not record his/her GPS location at any time. No data is collected, stored nor shared at any point.

## Algorithm (Pseudo-code)

*  Initialize M5 Stack devices
*  Connect the two devices to WiFi in both AP and station mode
*  Begin 2 Access Points on the M5 Stack and give the name “BoardA” to one and “BoardB” to the other
*  Get the number of nearby WiFi networks
*  While networks are found, compare their SSIDs
*  If SSID found equals “BoardB”, get its R4SSI value
*  If RSSI value > -47, emit vibration and print message “Please maintain a safe distance.”
*  Else, set the screen to green and print message “Safe”


