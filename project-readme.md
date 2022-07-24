# Tuiring-backend-test - Running the project
## Summary
The instructed call forwarding module was developed using Nest js( a progressive Node js framework) along with using typescript. 
For the purpose of storing calls data for activity logs mongo mongo db was used. 
In addition to that for api documentation swagger was used.
This document explains how to create run the project.  

## Packages Installation

1-Using npm install

- All the node modules associated with project will be installed
<!---Installs all node modules--->

2-Using npm run build

- For transpiling typescript code and generating dist folder that will contain javascript code
<!---Transpile code and creates dist--->

3-Using npm start

- Runs the project
<!---Runs the project--->

-Step number two and three can be skiped if we use step run start:dev

-Using npm run start:dev

- Transpile the code and Runs the project and updates dist with every change
<!---Transpile the code and Runs the project and updates dist with every change--->

## required env variables for this project

## Note: to get the values of the variables refer to 'tuiring-IVR-test app back-end (DEV)'

PORT=#Port goes here#
DB_URL=#Database url goes here#
###########
###########
TWILIO_AUTH_TOKEN=#Twilio Auth token goes here#
TWILIO_SID=#Twilio Sid token goes here#
