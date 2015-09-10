# Software Architecture Report 

# Stakeholders 

In order to find the necessary requirements and functionalities we have composed a list of stakeholders in our project. We’ve decided to split the stakeholders into small groups for better traceability. Our stakeholders for this project are:

### (Less-abled) product users
    
#### Why is this a stakeholder?

The end users of our product are people who are physically or mentally less able to perform household tasks. 

#### Interests

Having an improved quality of life due to the product, The end user benefits from having to perform less household tasks which in turn improves their QoL. Our end users are a stakeholder for this product because their needs will likely be partially fulfilled by our product.


### Quality Assurance Team  
  
#### Why is this a stakeholder?

They will test the product quality concerns.

#### Interests

QA team will test the product and makes sure it complies with quality standards set by the non-functional requirements


### Quality Care Testers
	
#### Why is this a stakeholder?

This group of stakeholders might have insights to make sure the product is and remains testable. 

#### Interests

A testable product of modules which can be tested separately. The testing team will test the product.


### Quality Care Developers

#### Why is this a stakeholder?
	
 They will be implementing the software for the product

#### Interests 

They are would like a maintainable system and an understandable design.


### Quality Care Researchers 

#### Why is this a stakeholder?

They will be conducting the research that will clarify uncertainties surrounding the product.
	
#### Interests

Clearly specified requirements and the subject(s) that needs to be researched.
	

### Quality Care Hardware Specialists

#### Why is this a stakeholder?

They will be responsible for the hardware designs needed by the product

#### Interests

The hardware specialists would like clear specifications what functions the hardware should be able to perform.


### Quality Care Managers

#### Why is this a stakeholder?

Management is a stakeholder 
	
#### Interests

Management wants a profitable product and to preserve the continuity of the company. 


### Quality Care Investors/Shareholders

#### Why is this a stakeholder?

They are the primary backers for Quality Care and the product.

#### Interests

They want the product to become profitable so that they can gain their investment back and make a profit


### Software Architects (FT 3) 

#### Why is this a stakeholder?

They want a good grade and well-functioning system.

#### Interests 

They are interested in a well performing system because they are responsible for the architecture 


### Health Insurance Providers

#### Why is this a stakeholder?

They may consider reimbursing clients for purchasing the product

#### Interests 

 A robot is cost effective alternative to real personnel and they would like to make more accessible for users in need of help


### Service engineers

#### Why is this a stakeholder?

They will responsible for maintaining individual units.

#### Interests

Remote analytics and modular hardware and easy product disassembly and maintenance instruction manual. Hardware that breaks down must be eligible repair and should have easy to replace parts for maintenance.


### External Manufacturer for the Hardware

#### Why is this a stakeholder?

The manufacturer is a stakeholder in this project to make sure the product can be produced once the designs are finalized. 

#### Interests

They require clear specifications on the hardware needed for the product and manufacturer must be able produce the given design. 	


### Quality Care Sales 

#### Why is this a stakeholder?

They will be responsible for selling the product

#### Interests 

They want a product that can be reasonably well sold.


### The Dutch Healthcare Authority (NZa)

#### Why is this a stakeholder?

The NZa is a stakeholder in this project because the product will be used in a medical fashion and can have effects on public health if it is not deemed safe. To make sure the product will comply with the latest rules and regulations the NZa is a definite stakeholder in this project.

#### Interests 

They want the product to be handled ethically and is safe for the public health
		

### Suppliers/Distributor/Trader/Retailer/Wholesaler

#### Why is this a stakeholder?

The distributor will deliver the product to retail stores or directly to the customers

#### Interests 

They want to easily be able to distribute and resell the product  

 
### Customer Support

#### Why is this a stakeholder?

They will get called when any users run into difficulty using the product

#### Interests 

Well documented instructions for troubleshooting


## Future Stakeholders: 


# Main Functionalities

After documenting the stakeholders of this project it was decided to create a list of functionalities for the robot. These functionalities are focussed on the end user and should all raise the quality of life for the user of this product.

1. Must be able to help people to get back up in the case of falling down
  In case the resident falls down and cannot get up then it should aid them by helping them stand back up

2. Must be able to remind users of (important) subjects/appointments
  Customers must be able to instruct the robot to remind them about an appointment/subject
  
3. Must be able to respond to a doorbell
  The resident/customer may not be physically able to respond to the door bell 

4. Must be able to make meals and/or drinks available
  The resident may not be able to cook for him/herself 
  
5. Must be able to clean the house 
  The robot is able to clean the house using a build in vacuum, thus removing the need for (extra) personnel to do so.

6. Must be able to administer medicine to the resident and keep the medicine stocked via prescriptions. 
  
# Requirements

After deciding on the set of main functionalities and stakeholders we’ve created a list of requirements in order to give our architecture more meaning. These requirements are split in functional and non-functional requirements. 
 
## Functional 

- Users should be able to decide how they like their meals
- Users should be able to customize the reminder settings
- It must be able to open doors and receive guests
- Unit must be able to notify the user that it is in need of servicing
- Unit must be able to analyze faults 
- Unit must be able to send diagnostics back to service engineers for analysis
- Unit must have modular hardware
- Unit must be easily disassembled 
- (Unit must have a (maintenance) instruction manual)
- Unit must have facial recognition 
- Unit must be able to recognize voice commands 
- Unit must be able to recognize hand gestures (sign language) commands
- Unit must be able to be controlled remotely via a remote. 
- Unit must be able to be configured
- Unit must have a display to be able to accommodate deaf or near deaf people 

## Non-Functional

- Unit must comply with health and safety regulations 
- Unit must be water resistant
- Unit must be assembled from components that are able to be tested individually 
- Unit must have replaceable parts 
- Unit must be accessible to users without prior knowledge
- Unit must be able to withstand shocks and possible falls
- Parts of the unit must be able to be recycled


# Referenced Architectures

http://www.mdpi.com/robotics/robotics-03-00181/article_deploy/html/images/robotics-03-00181-g007-1024.png
http://research.cens.ucla.edu/projects/2005/NIMS/software_arch/Figure1.gif
http://raweb.inria.fr/rapportsactivite/RA2009/lagadic/1.png
http://www.eng.newcastle.edu.au/eecs/fyweb/Archives/2004/c2007000/images/softwareA.png
http://cens.ucla.edu/projects/2005/Actuation/testbeds/Figure25.GIF


# Questions 

