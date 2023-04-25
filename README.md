# What is Flight Management System? 
 Flight Management System (FMS) is a computerized avionics system found in modern aircraft that assists pilots in flight planning, navigation, and performance monitoring.

The FMS uses information such as the aircraft's current position, flight plan, weather conditions, and aircraft performance characteristics to calculate the most efficient route to the destination. It also provides guidance for the aircraft's autopilot system to follow this calculated route

## What is implemented?

This is the basic model use to demonstrate the weather update and flight presence with name. 

# On Server (Express)
1) This is system use two ways to authenticate a user, user can login using facebook and a user can also enter credentials to signup/signin.
2) Authorization middleware has been implemented in this project.
3) JWT token autherization has been implemented.
4) Facebook token autherization has been implemented.
5) Server side routing has been implemented.
6) Mongooes database support is available.
7) Models use to store data in database.
8) Nodemon is isntalled to quick reload on server.
9) REST api is implemented.

# On Web application (REACT JS)
1) Signin and signup functionality is implemented.
2) User interactive dashboard is implemented.
3) Client side routing has been implemented
4) useState and useEffect hook is used.
5) Custom CSS is implemented.
6) Material Icon is used.

## How to run?

This application contain two folder fp_app that has the web application and fp_server that contain server of the application, we need to install node module for both side.

First a node must be install on your machine.
To install Node.js on your system, follow these steps:

Go to the official Node.js website at https://nodejs.org and download the installer for your operating system.

Once the download is complete, run the installer and follow the on-screen instructions.

In the installation wizard, you can choose whether to install the recommended version of Node.js or select a different version. You can also choose which components to install, such as the npm package manager.

After the installation is complete, open your command prompt or terminal and type node -v to verify that Node.js is installed and check the version number.

You can start using Node.js by creating a new file with the .js extension and writing your JavaScript code in it. Then, run the file by typing node filename.js in the command prompt or terminal.

That's it! You should now have Node.js installed and ready to use on your system.

1) Now open your vs code and import the folder of flight management.
2) Then move to the directory of fp_app in terminal.
3) Now type 'npm i' and press enter. This will install all the dependencies.
4) Now open another terminal in vs code and locate the fp_server.
5) Type 'npm i'.
6) Good news you have install all the required dependencies.
8) Now move to fp_server and create .env file for configuration.
9) Here you need to define link of your database (DBLINK) , port number (PORT) , jwt secret (JWT_SECRET) , Facebook app id (FACEBOOK_APP_ID) , Facebook app secret (FACEBOOK_APP_SECRET) and session secret (SESSIONSECRET).
10) Now move to fp_server terminal and type 'npm start',  This will start the server.
11) Now move to fp_app terminal and type 'npm start',  This will start the web application.

## Credential Page
![1](https://user-images.githubusercontent.com/65458742/234174215-a36655ee-3ff5-4b45-beea-7a569f635a4b.JPG)
![2](https://user-images.githubusercontent.com/65458742/234174218-3bd56f09-ca8e-4174-b4dd-ba7241b93aea.JPG)

## Demo

https://drive.google.com/file/d/1KRUec3a3P2_5gfpeoKXcoR8PVHHpKPTT/view?usp=share_link

## How to download

![3](https://user-images.githubusercontent.com/65458742/234175920-66058dfd-d372-4474-bd5f-0257e6461716.JPG)


## Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

Fork the Project
Create your Feature Branch
Commit your Changes
Push to the Branch
Open a Pull Request
