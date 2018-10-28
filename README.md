# Angular-Graph-REST-Sample

The repo is a starter sample for buindling MS Graph API applications using angular js. And this repo sample is created on top of [Angular QuickStart](https://developer.microsoft.com/en-us/graph/get-started/angular)

## How to Use ##

Follow the below steps to use this sample,

- Download or clone this Repo
- Extract the downloaded file
- Navigate to the project folder, where you have extracted or forked
- Open the project in your favourite editor. I am using **Visual Studio Code**
- Meanwhile, Create the Application Client ID by registring in [App Registration Porta](https://apps.dev.microsoft.com/)
- Copy the Client ID which is generated in App Registration.
![](https://raw.githubusercontent.com/ktskumar/Images/master/angulargraphrestsample/ClientIdUpdate.png)
- In the editor navigate to *Scripts/config.js*
  - Replace **&#60;Client ID&#62;** with your **Client ID** value
- Run the below commands in terminal
  -  **npm install**
  -  **npm start**
- After successfull build, nvaigate to the location http://localhost:8080
- Click **Connect** button to authenticate the App
![](https://raw.githubusercontent.com/ktskumar/Images/master/angulargraphrestsample/Connect.png)
- After connected, the view looks like below. Now you free to add your own code to connect Graph API
![](https://raw.githubusercontent.com/ktskumar/Images/master/angulargraphrestsample/AfterConnect.png)


*Cheers!*