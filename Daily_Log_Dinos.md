## 4/26/2017
* Registered wifi cards with Bates network
* Updated wpa_supplicant and interfaces files

## 5/1/2017

* Successfully SSH'd into Pis

## 5/2/2017
* Tried to set up adhoc network between RPis. Unsuccessful.

## 5/3/2017
* Continued to try to set up adhoc network between Pis. Still unsuccessful.

## 5/8/2017
* Spent entire day trying to figure out email script after flashing tablet SD card.
* Unsuccessful attempts connecting to internet.

## 5/9/2017
* Flashed headless RPi to working tablet RPi's image.
* Set up static IPs on both Pis for ethernet connections.
* Successfully tested remote file transfer over ethernet with SCP.
* Updated tutorial.
* Experimented with rsync (semi-successfully) to sync folders.

## 5/10/2017
* Realized there was a problem where we specified the wrong wlan interface in /usr/local/bin/startup.sh on the headless RPi. Changing it to wlan1 made it work.
* Fixed the lack of email from headless RPi
* Passwordless login from either pi to either pi
* Passwordless SCP for same
* Created shell script which transfers if ethernet is connected but not if the file already exists.

## 5/11/2017
* Fixed logic in script testing for eth0 connection.
* Set up cron job for running automatic file transfer.
* Set up notification window for complete file transfer and potential errors.
* Tried to run script on ethernet connection (post-up) and failed.
* Started building HTML form
* Successfully installed apache server.

## 5/12/2017
* Unsuccessfully flashed headless RPi's sd card.
* Initial set up of mySQL & PHP servers
* Downloaded additional apache components
* Changed index.html to sample form to change localhost page.
* Configured phpmyadmin

## 5/14/2017
* Successfully created a SQL DB and table in PHP.
* Semisuccessfully handled $_POST variables.
 
## 5/15/2017
* Successfully posted variables from html form to mySQL database.

## 5/17/2017
* Wrestled with GIT. — A
* Brought headless RPi up to speed. — A
* Researched copying databases remotely — D
* Researched merging two sql databases — D

## 5/18/2017
 
