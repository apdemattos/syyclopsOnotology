
## Syyclops Buildings Ontology
Based upon the COBie (Construction Operations Building Information Exchange) Standard

![](<SyyclopsOntology.png>)

## COBie Background

Construction handover of information has been a struggle, information was traditionally provided as paper drawings and documents in binders. The industry has been slowly moving into the digital world and the digitalization of this inforamtion. Owneres and Facility managers have started using CMMS (Computerized Maintenance Management System) systems to support their daily task of operating, maintaining, and managing the facilites. In order to do this they need information about the building and the equipment in need of maintenance and inspections. This info. is usually locked down in pdf documents, so to set up a CMMS system the manager needs to hunt down maintenance schedules and operating instructions and link or copy the data into the system. 

COBie created a standarized template to organize this information during the construction process and handover this information to a facility manager so they have it readily available when maintance or management is required. 

## Ontology Overview 

**Component** - The central most important piece. The owners need to keep track of what equipment they have, who made it and delivered it, when it needs maintenance, how to inspect it and track history of service requests and works orders. 

**Type** - Most components are defined by their type. When you install many instances of a common product the common information goes here.

**Space** - Spaces are normally rooms of a building. However there may be exceptions such as parking lots, roofs, etc. Also larger rooms may be divided into spaces when it makes sense. Spaces are important for locating equipment, all equipment should be tagged with spaces where you access them for operation or maintenance. 

**Zone** - Grouping of spaces that can be flexible. Zones can be used to divide facilites into ventilzation cones, access zones, etc. 

**System** - Grouping of equipment such as AHU system or condensor water system

**Facility** - The Buildings themselves

**Floor** -  Part of the building structure and a way to group spaces

**Document** - Documentation about the delivered equipment, usually tagged to a Type. Can provide maintenance intructions. Some Documents may also be tagged to systems or facilities 

*Document Types:*
- Cut Sheets/Specs
- Videos 
- Preventative Maintenance 
- O&M Manuals

**Attribute** - Can be used to tag custom data, similar to properties in the IFC data model

*Attribute Types:*
- Schedule

## Sensors

*Input Signals are reading data, Output Signals are commands or controls*

**Digital Input** - binary inputs (0 or 1), used to check the status of any device whether it is ON or OFF

**Digital Output** - binary outputs (0 or 1), used to control any piece of eqipment ON or OFF

**Analog Input** - Analog signals are variable that have multiple states. AI signals can represent temperature, or rate of flow

**Analog Output** - Also a variable that can be used for opening a valve to a desired position

**Virtual Point** - A programmed point that sits in software such as a Set Point

