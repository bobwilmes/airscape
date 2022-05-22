# Air Scape  

## Hackster.io Project - Particulate detector for air quality using Sony Spresense  

### This is the index.js submission for Alexa Skill named ("air scape")

### Project: Air Quality particulate matter tracker with Amazon Alexa   

### Team members: Bob Wilmes   

###Sponsor: Hackerster.io and Sony  

Tools and Environments: AWS Lambda, Alexa Skills Kit, Node.js

###Goal:  
This project utilizes a mobile IoT platform comprised of a Sony Spresense and an environment sensor (CO2, temperature, barimetric pressure and humidity) (Sparkfun) 
and a particulate matter sensor (Sensirion/Sparkfun), as well as a GPS/GNSS positioning sensor, a MPEG camera and a LTE cellular modem. The benefit is to use
mobile drivers like Lyft/Uber drivers to collect the data (referred to as the "Air Scape") to the AWS cloud. A second component uses the Alexa voice application
to replay the gathered data in an audio summerized format.


Overview and Functionalities:
The Air Scape uses AWS Lamda serverless (Node.js) computing to serve Alexa skills. It uses the Amazon S3 database to log the IoT platform measurements.
  
