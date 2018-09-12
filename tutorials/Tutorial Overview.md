# Tutorials Plan

## Prerequesites

## Options

1. Jupyter notebook that grabs FHIR resources and does some calculation to produce some clinically relevant output [no experience/scalable]
2. SMART app that implements an app idea from below [some experience/scalable]
3. CDS hooks using our or the Cerner tutorial (or a combination) [medium experience]



## Tutorial Possible Themes

### incorporating external data/functionality

Specific idea 1: Hitting BlueButton API to get claims data
Specific idea 2: Use external tool for clinical feedback/decision support
Specific idea 3: Up-to-date or drug/drug interaction APIs to show relevant
Specific idea 4: Include sources of patient data outside the EHR (e.g. fitness trackers, sleep data, etc)

### care coordination

Specific idea 1: SMART patient list with list admin functionality (Add/remove patients, make custom cohorts, send messages/set reminder)’

### decision support

Specific idea 1: Risk calculator
Specific idea 2: CDS hooks to invoke 


### patient facing

Specific idea 1: Messaging/communication
Specific idea 2: Patient reported outcome



## Tutorial Levels

### Level One
A Jupyter notebook that illustrates:
1. Grabbing FHIR resources from a given FHIR endpoint. 
2. Manipulating data in some way (internally/externally) to produce interesting outcome

#### Teaching Objectives
- Mapping FHIR Resources to a real-world tool / API

#### Required Knowledge

#### Resource / Calculator Options
- Publicly-available APIs for health calcultors
- Custom implementation of a simple health calculator


### Level Two
A client-side (uses javascript client?) or server-side? (uses python client) app that is able to be launched from the HSPC sandbox.

#### Required Knowledge

#### Resources

### Level Three
A CDS Service that interacts with the HSPC Sandbox / CDS Hooks Sandbox to provide clinical decision support / public health advisories / anything that might be relevant to the subject given some triggers. 

** Intro to CDS Hooks
** Intro to possible triggers

#### Teaching Objectives
- CDS Hooks Concepts, API, & Interaction Pattern
- Integration into real clinical scenarios - right time, right place, right advice
- Demonstration of flexiblility and capabilities of CDS Hooks
  
#### Required Knowledge

#### Resources