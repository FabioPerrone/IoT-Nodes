# IoT-Nodes
Define IoT Nodes Specs  
Two tier concept   
one part (System on Module) that has the embedded intelligence and can have onboard a linux pc  
one part (Sensors on Board) that has the sensor and the bus (copied fron the specs of Texas)with all connectivity  

## The IoT data flow

* An untraditional way of describing IoT Environment*

### Volume 1 - On the sensor
Once data is collected by the device, it can:
  - Step1. Be used to trigger particular actions if a condition is matched or not. And then continue to Step2 or directly to Step3.
  - Step2. Be aggregated with other data. And then came back to Step1 or continue to Step3.
  - Step3. Be sent *somewhere else* 
  
  
Then, what does *somewhere else* means in this scenario?

The possible destinations are 3:
  - If the the sensor-to-sensor communication is enabled, the collected data could be sent to other sensors according to some logics previously defined, or to a specific sensor that act as a master among the others.
  - If an edge node exists, data could be sent to it. What's an edge node? An Edge node is device with no battery contrains, with more computational capabilities and more network bandwidth than a sensor.
  - If the sensor is enabled to connect with, data could be sent directly to the entity in charge of collecting all data from all sensor. The endpoint of this entity could be for example an mqtt broker.
  
### Volume 2 - On Edge Device

Once data is collected by the Edge device...



Sensor node network
Small  
Medium (520)  
Large (730)  

Portal concept (IoT device instrument manager) resin.io  

Legacy connection concept  


## Hardware
  ### Sensors
  
  ### Edge Devices
  
## Software
  ### Sensors
  
  ### Edge Devices

