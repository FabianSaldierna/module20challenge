# module20challenge
Solved code for the module 20 challenge

## Deployed application
https://module20challenge-dfub.onrender.com

## Description
This project solves the challenge for Module 20 with GitHub Actions. It contains two yaml files: 
  - The first one is triggered on pull_requests to the "develop" branch.
  - The second one is triggered on pull_requests to the "main" branch.

## Usage
1. When commiting changes to "develop" branch, wait for the cypress tests to run:

  ![image](https://github.com/user-attachments/assets/93cc6f3b-ecbd-4417-9b41-8ee2e7e25083)

  You may check the "actions" tab on GitHub for a more detailed look of the tests:

  ![image](https://github.com/user-attachments/assets/2f7e1cf9-ef93-479c-ab6b-932b2ba18541)

2. When commiting changes to "main" branch, wait for the render deployment test:

   ![image](https://github.com/user-attachments/assets/2dc0ab32-ef38-4ad4-82d2-fdb6fc1c3f9e)

  For a deatailed look of the test, go again to the "actions" tab on GitHub:

  ![image](https://github.com/user-attachments/assets/2ff5557a-ad40-4af4-b73a-7d0895529003)

  You may check on Render the status of the deployment:

  ![image](https://github.com/user-attachments/assets/cf525d8c-f3f7-47a5-b307-eb397f4b78a6)


## Installation
In order to use the application, you may need to install NPM packages with:

  npm i

Then you may compile the client and server applications:

  npm run build

Create the seeds with:

  npm run seed

To run the cypress tests, use the following command:

  npm run develop (for dev environment )
  npm run start ( for production)

## Credits
Fabian Saldierna.

## License
An MIT standard license was used. You may refer to it from the repo.

## Features
Implemented GitHub actions to test cypress and deploy on render.
