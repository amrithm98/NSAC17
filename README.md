# Sunshine-NSAC17
<br>

Nasa Space Apps Challenge 2017- "Earth and Us/You are my sunshine"
<br>

<b>Ionic 2 Application</b>
<br>

Team :Gryphons
<br>

<img src="http://ieee-link.org/wplink/wp-content/uploads/2016/04/pjimage.jpg">
<br>

1. Cross platform application connected to firebase
2. User can enter solar panel specifications and get output predictions based on user location and other data.
3. User can set priority on devices and devices that can be used with available power can be identified.
4. User can calculate required tilt of the panel based on the current location.
<br>

You need to install ionic and cordova on your machine by running `npm install -g ionic cordova`
<br>

Instructions are the same for both windows and linux
<br>

<b>To build the application :</b>
1. Clone the application `git clone https://github.com/amrithm98/Sunshine-NSAC17.git`
2. `cd` into the project directory and navigate to the directory containing `ionic.config.json`
3. `npm install`
4. `ionic state restore`
5. `ionic serve` to run the application on the web browser

<b>To run the application on an android device :</b>
<br>

Follow the above for steps and after that do the following:
<br>

Make sure you have Android Sdk and Java Configured with the environment variables.
<br>

Connect an android device to the machine,allow USB debugging and then :

1. `ionic build android`
2. `ionic run android`

This will run the application on your android device. `
<br>

You can build the application for iOS by running 
`ionic build ios`
