## Functional Safety of a Lane Assistance System (Self-Driving Car Engineer Nanodegree)
In this project, simplified versions of functional safety documents for 
a lane assistance system safety case are developed. The functional safety case is developed
under the ISO 26262 standard.
A safety case is a collection of documents proving that a project has made a vehicle safer.

#### Documents
- [Safety Plan](PDFs/01_SafetyPlan_LaneAssistance.pdf)
- [Hazard Analysis and Risk Assessment](PDFs/02_HazardAnalysisAndRiskAssessment_LaneAssistance.pdf)
- [Functional Safety Concept](PDFs/03_FunctionalSafetyConcept_LaneAssistance.pdf)
- [Technical Safety Concept](PDFs/04_TechnicalSafetyConcept_LaneAssistance.pdf)
- [Software Safety Requirements and Architecture](PDFs/05_SoftwareRequirementsAndArchitecture_LaneAssistance.pdf)


The [Udacity](https://udacity.com) has provided template files for the above documents. 
These template files can be found in [Templates](Templates) directory. 
The filled non-editable versions of these documents can be found in [PDFs](PDFs) directory. 
They preserve the proper formatting of the documents and tables. 
The filled (finished) documents in editable formats (\*.docx and \*.xlsx) can be found in [Documents](Documents) directory.

#### Details
The project is developed under the ISO 26262 standard. 
The ISO 26262 standard, titled "Road vehicles --- Functional safety,"
is an international standard for functional safety of electrical and/or electronic systems 
in production automobiles defined by the International Organization for Standardization (ISO) in 2011. 
More information about the standard can be found in [Wikipedia](https://en.wikipedia.org/wiki/ISO_26262).

The project considers the functional safety of a lane assistance system. A lane assistance system 
is a kind of an [Advanced Driver Assistance System (ADAS)](https://en.wikipedia.org/wiki/Advanced_driver-assistance_systems)
consisting of
1. [Lane Departure Warning functionality](https://en.wikipedia.org/wiki/Lane_departure_warning_system)
    - A mechanism designed to warn the driver when the vehicle begins to move out of its lane 
    (unless a turn signal is on in that direction) on freeways and arterial roads.
2. [Lane Keeping Assistance functionality](https://en.wikipedia.org/wiki/Lane_departure_warning_system#Lane_keeping)
    - A feature that automatically takes steps to ensure the vehicle stays in its lane 
    by moving the steering wheel so that the wheels turn towards the center of the lane when necessary.

The [Safety Plan](PDFs/01_SafetyPlan_LaneAssistance.pdf) gives an overview of how to achieve a safe system. 
It specifies what system is under consideration, the goal of the project, what steps need to be taken to ensure
safety, the roles and personnel involved in the project, and the project timeline.

The [Hazard Analysis and Risk Assessment](PDFs/02_HazardAnalysisAndRiskAssessment_LaneAssistance.pdf) makes 
a situational analysis, identifies hazards, classifies them according to severity and probability of occurrence
calculates the [ASIL](https://en.wikipedia.org/wiki/Automotive_Safety_Integrity_Level), and derives safety goals.

The purpose of the [Functional Safety Concept](PDFs/03_FunctionalSafetyConcept_LaneAssistance.pdf) 
is to refine the safety goals in what is called functional safety requirements and then allocate 
these safety requirements to the relevant parts of the system diagram. 
It involves expanding the system architecture with new element blocks, if necessary, 
and refining the system architecture to handle the new requirements. 
The functional safety concept does not go into technical details; 
it looks at the general functionality of the lane assistance system.

The [Technical Safety Concept](PDFs/04_TechnicalSafetyConcept_LaneAssistance.pdf) 
looks at the technical implementation of the lane assistance system. 
Its purpose is to turn functional safety requirements into technical safety requirements 
and allocate those technical safety requirements to the system architecture. 
The [Technical Safety Concept](PDFs/04_TechnicalSafetyConcept_LaneAssistance.pdf) 
considers the system at a more technical level, thinks about sensors, control units, and actuators. 
Technical safety requirements are general hardware and software requirements but without getting 
into specific details.

The purpose of the 
[Software Safety Requirements and Architecture](PDFs/05_SoftwareRequirementsAndArchitecture_LaneAssistance.pdf) 
document is to develop software requirements and metrics against which the lane assistance system can be verified, 
that ensures its functional safety. 
These requirements are even more detailed than the technical Safety requirements.

Detailed project instructions can be found in the original project repository provided by 
[Udacity](https://udacity.com): 
[https://github.com/udacity/CarND-Functional-Safety-Project](https://github.com/udacity/CarND-Functional-Safety-Project).
