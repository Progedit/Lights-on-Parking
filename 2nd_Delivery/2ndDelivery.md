# 2nd Delivery
## Comments received during the 1st Delivery
### 1. Not extend the project and to focus on the parking problem
  Initially we had thought of creating a double functionality, both that of smart parking and that of street lighting, 
  but we were advised to focus exclusively on the parking part for the moment.
### 2. Requirements
  In the first delivery, the project requirements were too general and bland. We did not focus on a particular study area but on a huge city.
### 3. Accuracy
  We haven't supported our ideas with measures and numbers.
### 4. Storyboards and Personas
  The use of storyboards and personas weren't necessary, and so we don't use these methods.
## Changes
  During the first delivery, several problems arose about how we had set up our project.

  The most relevant changes for the moment are on the place where to install the device and on the functionalities that 
  the project offers: initially we had thought of installing a pole near each parking lot, 
  so as to create a double functionality (smart parking and street lighting), 
  but thinking exclusively about the parking functionality we decided to change our mind and install the device under the ground. 
  This solution is better than the previous one since the positioning of the device below the parking surface provides the safest and 
  most lasting installation over time: in fact, installing this product below ground level is an excellent way to protect the sensor from bad weather and 
  excessive temperature changes, not to mention mechanical shocks and vandalism.

  Another point on which we focused is that relating to the search for requirements, 
  based on a form that we sent to possible users, which underlined how much the problem of finding a parking space can be something that needs to be improved, 
  regardless of the area. urban area of which you belong, or where you live / work.

  The storyboards and personas were used to better understand what the actual requirements were at the basis of our project. 
  In particular, the first storyboard helped us to highlight the problem of traffic congestion and pollution as the main problems to be faced. 
  Both of these problems exist independently of the parking problem, but surely the continuous search for a parking space blindly leads to 
  a specific traffic generated by those who travel around the city with their car only and exclusively because they need a parking space.
  
## Technical Work

Compared to the first delivery, we started working on making our device, building the circuit and writing the code. The circuit consists of the nucleo board and an ultrasonic sensor, to notify the presence or absence of the vehicle.
Later the data collected by the circuit is sent to the database on AWS.
Subsequently we created an account on AWS and a database on DynamoDB, for  store the data and make them available and consulted by a hypothetical user.
We also tried to establish the connection between the device and AWS, but the service is not yet functional at the moment as we have encountered several problems in the implementation, so we wrote a script in python that simulates the data collection (therefore it does not collect real data) and sends them to the cloud via the MQTT protocol.
Finally, we dedicated ourselves to evaluating performance from an energy point of view, focusing on the theoretical part and based on the current state of the prototype.

## Missing Functionalities

List of the functionality that is still missing:
- Evaluation of battery consumption sending data.
- Precise evaluation of data by analyzing with IoT-Lab / INA.
- Connecting devices with Lora and edge computing.
- Web Dashboard.


