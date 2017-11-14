 
*** Project Background and Objectives  
FCA has developed different regional Manufacturing solutions to provide its internal and external processes services with value-added insights and meaningful data. The solutions currently available are using different models, from traditional databases to Big Data solutions.  

**	Objectives
FCA invites the supplier to submit a proposal demonstrating their capabilities to understand and develop an IoT ecosystem for FCA, identifying:  

•	The capabilities of adapting to existing standard (CARS Standard) and define the future roadmap to standardisation and integration for IoT Nodes (2.1)  
•	The capabilities of providing a roadmap to the evolution of the Nodes (2.1)
•	The cloud adoption strategy (2.2)
•	The analytics tools (2.2)
•	The roadmap to the common data lake (2.2)
•	The best development platform and workflow for the data scientists and analytics app developers (2.3)
•	The actionable space of the data, whether that be a dashboard, a specific application, or an API (2.4)
•	Evolution of the overall current scenario which is actually involving Business Intelligence, DWH, Adv. Analytics and Web applications-PCF (3)
o	The new scenario should take into consideration an on-prem., in cloud and hybrid situations
o	Should also highlight which components (especially in the hybrid scenario) have to be on-prem. or in cloud
o	Licensing and support options (including cost scenarios) for existing software such as Cognos, QlikView, Qlik Sense, DataStage, on prem and in the cloud
•	A comparison between the single proprietary components of the on cloud solutions of the major vendors/platforms; as an example: Hadoop Big Data Processing On Premise can be mapped on Amazon EMR, Google DataProc, Azure HD Insight. Since Cloud vendors propose different pricing models, FCA needs to understand which is the best choice in terms of costs and capabilities
•	A recommendation regarding the possible centralization of machine learning data and services vs. delocalization of the same services (i.e.: integration with Connected Vehicles and Industry 4.0)  
•	A perspective on an architecture that addresses global, regional, functional and distributed needs – recommendations on what would go where from a data and application perspective, how, why, etc. including interconnectivity with existing initiatives including Connected Vehicle Analytics, Manufacturing IoT, etc. 
•	Propose a global architecture and workflow process that will provide a flexible and sustainable data governance to support the current needs of FCA.
•	Provide a cost estimate to develop a Global Integrated Data Analytics Platform and all components surrounding the Big Data and Analytics environment
Supplier is advised to align responses to all demands specified in this RFI. Responses not in compliance with the terms or conditions of this “Request” shall be considered an unacceptable proposal.
The objectives for this request for information (RFI) are to select a subset of consultants to submit via a RFQ (Request for Quote) a proposal to build out a Big Data and Analytics Roadmap strategy for FCA.


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

If needed, further intelligence could be added to the IoT board previously introduced, allowing the developer to access to the board functionalities at an higher level interacting directly with the OS, by adding a microprocessor to the Board. The cost of this additional computational power is an increase of power consumption and the effort of integrating the underlying board with the microprocessor.

** 2.1 CARS Specifications  
  
** 2.2 IoT Nodes Specifications  
  
** 2.3 Things-to-Cloud APIs  
  
  

## The IoT data flow

*An untraditional way of describing IoT Environment*

### Volume 1 - On the sensor
Once data is collected by the device, it can:
- Step1. Be used to trigger particular actions if a condition is matched or not. And then continue to Step2 or directly to Step3.
- Step2. Be aggregated with other data. And then came back to Step1 or continue to Step3.
- Step3. Be sent *somewhere else* 

<div style="text-align:center"><img src ="https://raw.githubusercontent.com/FabioPerrone/IoT-Nodes/master/iotnodesteps.png" /></div>
  
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

