# Crowd Counter with NodeJS

A WoT Project for Raspberry Pi

Members:

Armocilla, John Mar Y.

Del Rosario, Vance

Reyes, Justin Rupert F.

Rudico, Ericka F. 

## Pre-req
1. Node installed
2. Visual Studio Code

## Running the Codes
0. Open Terminal with 
```
ctrl + `
```
1. Clone the github repository with 
```
git clone https://github.com/VanceDR/Crowd-Counter-Test.git
```
2. Go to the folder by 
```
cd Crowd-Counter-Test
```
3. Install packages needed using 
```
npm install
```
4. Run the app using 
```
npm start
```
5. Open the App in browser with
```
localhost:8484
```


## Implemented
1. Counter
2. Real-Time updated with Socket.io
3. Charts with Charts.js
4. Functioning Updates from counter to graphs

## To-Do
1. Integration of the PIR Sensor to Control the increment and decrement of the values in the webapp
2. Need Database to collect data over time


## Screenshots
![Main Page](docs/main.png)
![People Count](docs/PeopleCount.png)
![Peak People Count](docs/PeakPeopleCount.png)