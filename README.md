# CP317_KingdemereArena
Course: CP317

Group Members:
- Jonah Eichler (190207850)
- Daniel Faseyi (190850640)
- Dharmik Patel (180343800)
- Jagnoor Nijjar (190485190)
- Adil Nawaz (190956140)
- Stephanie Chan (190628550)
- Aozhou Hao (183152440)



# Introduction

This repository contains our code files for our Kingdemere Arena Ice Hockey Rental Application in react native for CP317. This repository is made up from React Native and Javascript components. To accommodate all the functionalities of our application, we implemented a log-in program, Calendar, and review. We used VS code as our primary IDE and imported React and Logo classes as well as our Customer Button and Input classes. 

Important Note: Due to time constraints there are alot of missing functions , features and compatability issues we did not get to , especially with the troubles of setting up the simulator and libraries and frameworks we had along the way. Additonaly, a folder Called Screenshots is provided and will contain examples of our different screens in case you can’t get it to run on your computer.

## Tutorial


## Installing Prerequisites


### Setting up your IDE

1.) Install the IDE of your choice. In our tutorial we are going to be using Visual Studio Code.
   Go to https://code.visualstudio.com/download and download it for your respective system.
   
 ### Setting up React Native Environment  
   
2.) Once you have your IDE setup and installed. You are now going to install React Native the language used to support our IOS/Android Multiplatform Applications. 

 - First Make sure you have NodeJs installed on your computer. If you don't have it installed go to https://nodejs.org/en/ and download the LTS (16.4.2) or the Current version (17.8.0). 

- Now you are going to install and setup the React Native environment to do so go to the following link https://reactnative.dev/docs/environment-setup and follow the instructions on your PC terminal. (Make sure you have your IDE closed otherwise you will get an error.)

### Opening the Github Repo in your Environment

Now that you have your IDE Installed along with React Native Environment setup. You can now open the Github repo in your own Environment. 

Firstly , Open up the terminal in your computer as administrator and type the following command: 
```
$ git clone {https://github.com/YSaintL/CP317_KingdemereArena}
```

Then go to the directory your downloaded repository is stored in using the ``` Cd ``` commands. 
For example on Mac:  
```
cd desktop
cd CP317_KingdemereArena 
```
For Example on Windows:
```
cd destkop
cd ./CP317_KingdemereArena

```
Otherwise you can just go to Visual Studio Code Press 'File' -> 'Open Folder' and open the repo folder.

### Switching Screens

The Kingdemere Arena has 7 different screens available to the user, in order to access each screen the user is required to change a single statement in the file App.js and this is necessary as the screens are not connected to each other due to time constraints.

Below are the 7 statements that are gonna be used to switch the screen:
- SignInScreen
- SignUpScreen
- ConfirmEmailScreen
- ResetPasswordScreen
- ConfirmResetScreen
- CalenderScreen
- Review Screen

Example: 
![image](https://user-images.githubusercontent.com/102828378/161886146-ecaf806a-d61b-4e7e-8b49-117803e5cbcd.png)


### IOS Simulator. (Optional Recommended)

Once the project is open on the IDE Environment , In order to open up an IOS Simulator through the expo native client. Go to the appstore on your mac device and download Xcode. Once Xcode is open follow the following steps:

1) Make sure Xcode is set in the command line. To do so go to top left of your screen. 
      Click: Xcode -> Preferences -> Locations and ensure in the command line tools your Xcode version is selected.
      <img width="678" alt="image" src="https://user-images.githubusercontent.com/77247670/161879225-1470a3b9-8460-49cf-ac46-6d91e7486dcc.png">


2) Test out an IOS Simulator to see if it works go to the Xcode menu at the top left off your screen select 'Open Developer Tools' -> Simulator as shown in the screenshot provided below.
  <img width="678" alt="image" src="https://user-images.githubusercontent.com/77247670/161879803-566c8006-b93e-41f0-b793-6693c5c5459f.png">
 
3) Then go to 'File' -> 'Open Simulator' -> 'IOs 15.4' and you can select any of the devices of your choice.
   
    <img width="678" alt="image" src="https://user-images.githubusercontent.com/77247670/161880166-4864cdc4-c3ff-4bed-bd73-249da147d0a5.png">
 
 4) Once you have set your default simulation device. You can now go to the terminal in your programming environment and open the repository on your Simulator. 

<img width="678" alt="image" src="https://user-images.githubusercontent.com/77247670/161883678-34d6047b-78c9-4088-9482-a021598a7b1c.png">

As shown in the picture above to run it on the IOS Simulator we have configured, all you have to do is run the following command in the terminal within the location of your repository.

```
 - npm start
```
It should then allow you to open it up on your web browser by pressing 'W' and to 'i" to open it up within the simulator as shown in the screenshot above.

