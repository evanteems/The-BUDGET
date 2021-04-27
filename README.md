# The-BUDGET

# Table Of Contents
  1. [Description](#Description)
  2. [Installation](#Installation)
  3. [Usage](#Usage)
  4. [License](#License)
  5. [Questions](#Questions)

# Description
The budget tracker is a utility app for tracking your funds and expenese over a period of time. It is a PWA (progressive web app) that has full online functionality. The Budget Tracker uses a multitude of various data storage methods to ensure that the data is accounted for even when this device or server is completely onlone. This app can be installed from any browser.

Here is a screenshot of the functional app
![19-pwa-homework-demo-01](https://user-images.githubusercontent.com/74634325/116167707-a0ae4900-a6b5-11eb-9465-931a25597c05.png)

# Installation
To install this application, head to the [Budget Tracker App](https://budgets-518.herokuapp.com/) in your browser. This is how to install this to your desktop from Google Chrome:
  1. On your computer, open Chrome.
  2. Go to the webiste you wish to install
  3. At the top right of the address bar, click the ...
  4. Next click more tools and create shortcut.
  5. If everything is done correctly your desktop should have this:
![Budget(2)](https://user-images.githubusercontent.com/74634325/116168465-4b733700-a6b7-11eb-945d-efe7306f80f6.png)

To download the Budget Tracker for ios or mac using safari navigate to the Budget Tracker App in your browser and follow these instruction:
  1. Navigate to the website you want to add as a PWA in Safari.
  2. Tap the 'Share' button, scroll down and tap 'Add to Home Screen.'
  3. Enter the name for the app then tap add.
  4. The PWA will show up on your home screen or desktop just like native IOS app.

To run this server on your local computer follow these instructions:
  1. Navigate to this GitHub repository(https://github.com/evanteems/The-BUDGET) in your web browser, then click the green dropdown menu that says "Code". Copy the SSH key to your clipboard and then open your terminal.
  2. In your terminal navigate to the directory you wish to insert this repository.
  3. Type "git clone" into your command line and paste the SSH key you copies previously from your browser, then hit enter. If done correctly, you should be able to see this repository on your desired location. Due to how big the file size, you will need to have Node.js installed into your computer!
  4. Once Node.js is successfully installed onto your computer navigate to the project's root directory in your terminal. In vscode, click the terminal button and go to "Open in intergrated terminal"
  5. Type the following command to install the proper node modules: "npm install"
  6. Check your newly downloaded "node_modules" folder to ensure that the correct packages have been install. You will now need to install the following packages 
  "compression": "^1.7.4",
  "express": "^4.17.1",
  "mongoose": "^5.5.15",
  "morgan": "^1.9.1".
For these packages to be installed, write the follwoing command "npm install <node module name>". They should allbe installed individually!
  7. This application also needs to use Mongodb to store json documents and data. To download the free version of Mongodb and set up your database please click this link and follow the instructions to download Mongodb Atlas and create a NoSQL database collection:[download MongodB Atlas](https://docs.mongodb.com/manual/installation/).
  8. If you made it to this point, you have successfully downloaded the repository, downloaded all the dependencies, and even got Mongodb on to your computer! Go into your terminal and type: "npm start". Doing this will start up the application locally.

# Usage
To use this application, you must first have the application open in your browser. You will be prompted with how the application looks on the screenshot above. For the textarea labeled "Transaction Amount". Once the name and the amount is entered in press "add funds" or "subtract funds" button the complete the process. The amount will be added or subtracted and the graph will show a record of total funds. 

# License
license
Apache2.0
Apache2.0 Copyright [yyyy] [name of copyright owner]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

# Questions 
If you have an questions or want to collaberate with me, you can find my github at: (https://github.com/evanteems)
