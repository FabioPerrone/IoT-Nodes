# IoT-Nodes

For the consumer, a smartphone is a **single atomic** object that allows to communicate with other people, to take pictures, to surf the web, at the same time. It is actually an object made of other objects: antennas, cameras, a wide variety of sensors, a processor, a memory device and so on.

Similarly, an IoT Node is not an **atomic** component, but it is composed by several **bricks**.

The key component are:
- Sensors
  - Thermal
  - Light
  - Gyro
  - ..
- Microcontroller
- Bus
- Network Interface
  - Wifi
  - Ethernet
  - ..
  
These components can make an IoT board:

<div style="text-align:center"><img src ="https://raw.githubusercontent.com/FabioPerrone/IoT-Nodes/master/iotboard.png" /></div>

The next step is to add some intelligence to the IoT board previously introduced, allowing the developer to access to the board functionalities at an higher level, interacting directly with the OS. 

## The IoT data flow

*An untraditional way of describing IoT Environment*

### Volume 1 - On the sensor
Once data is collected by the device, it can:
- Step1. Be used to trigger particular actions if a condition is matched or not. And then continue to Step2 or directly to Step3.
- Step2. Be aggregated with other data. And then came back to Step1 or continue to Step3.
- Step3. Be sent *somewhere else* 
  
  
In this scenario, *somewhere else* means 3 possible destinations:
  - If the the sensor-to-sensor communication is enabled, the collected data could be sent to other sensors according to some logics previously defined, or to a specific sensor that act as a master among the others.
  - If an edge node exists, data could be sent to it. What's an edge node? An Edge node is a device with no battery constrains, with more computational capabilities and more network bandwidth than a *standard* sensor.
  - If the sensor is enabled to connect with, data could be sent directly to the entity in charge of collecting all data from all sensors. The endpoint of this entity could be for example an mqtt broker.
  
### Volume 2 - On Edge Device

Once data is collected by the Edge device...


# The Sensor network

Sensor node network sizes:
  - Micro     (<50)
  - Small     (>50 & <500)
  - Medium    (>500 & <800)  
  - Large     (>800)  

Topologies:
  - Bus
  - Tree
  - Star
  - Ring
  - Mesh
  - Circular
  - Grid

# IoT device management

Portal concept (IoT device instrument manager) resin.io  


# Integration with the Industrial Environment

Legacy connection concept  


## Hardware
  ### Sensors
  
  ### Edge Devices
  
## Software
  ### Sensors
  
  ### Edge Devices

