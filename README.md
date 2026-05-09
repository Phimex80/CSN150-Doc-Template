# Cybersecurity : CSN150
Project: ESP32 camera streaming 

## Purpose
Set up ESP32 and Arduino enviornment. Execute sketch " Wifiscanner" with ssid and password 

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation and tools
https://lastminuteengineers.com/getting-started-with-esp32-cam/

##### Video 1: 

##### Other Links: 

##### AI GPTs used

## Steps I followed
1.i connect ESP32 CAM on port using  usb port and also connect to arduino. using the example EPS webcam, change the ssid and password to my own , changing the baud to 115200 and i uploaded the code. 

 
**Problem:** A fatal error occurred: Could not open COM4, the port is busy or doesn't exist. (could not open port 'COM4': FileNotFoundError(2, 'The system cannot find the file specified.', None, 2)) Hint: Check if the port is correct and ESP connected Failed uploading: uploading error: exit status 2
**Solution:**
This error means your computer can't find your ESP board on COM4.


## Final Report
