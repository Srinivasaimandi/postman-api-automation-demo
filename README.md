# Postman Api Automation Demo
## ❓What is this Repository about?
This repository contains demo test automation scripts built with Postman for the following websites
  - http://rahulshettyacademy.com
  - https://reqres.in

  ## ⌘ Getting Started
  **Prerequisite**
  - setup node: [Windows][1] | [Ubuntu][2] | [macOS][3]

**Setup**
- Open a terminal and install the dependencies using the below command at global level

  **```npm install -g newman```**
  **```npm install -g newman-reporter-htmlextra```**

**Running the scripts**
- run the below command to run the postman collection against an environment

  **```newman run postman-automation-demo.postman_collection.json -e postman-automation-demo-env.postman_environment.json -r htmlextra```**  
  <br>

[1]:https://www.geeksforgeeks.org/install-node-js-on-windows/
[2]:https://www.geeksforgeeks.org/installation-of-node-js-on-linux/
[3]:https://www.geeksforgeeks.org/how-to-install-nodejs-on-macos/
