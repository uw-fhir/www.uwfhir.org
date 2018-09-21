# Overview
The UW FHIR Workshop Tutorials will take place on Sunday, September 23 in room C123 in [Building C](https://www.uwmedicine.org/research/sites-facilities/slu/maps-contacts) at the UW Medicine - South Lake Union Research Hub. 

The address of the location is [850 Republican St, Seattle, WA 98109](https://goo.gl/maps/Z3wTR9A5iVP2). 

The tutorials will consist of two sessions - one in the morning, one in the afternoon - with a lunch break between.  

The morning session will introduce FHIR, FHIR Resources, and the ClinFHIR tool. 

The afternoon session will start with a walk-through for using FHIR APIs to retrieve FHIR resources needed for calculating the [Framingham Cardiovascular Risk Score](https://en.wikipedia.org/wiki/Framingham_Risk_Score).

For the rest of the afternoon, participants will choose from 3 different tracks and work together in small teams on more advanced projects. 
We will aim to create diverse teams that include at least one clinician and one developer and encourage the kind of collaboration between individuals with various backgrounds and skill sets that is crucial in healthcare IT.

Please contact <a href='mailto:workshop@uwfhir.org'>workshop@uwfhir.org</a> if you have any questions or issues finding us!

# Agenda

| Time Slot          | Instructor(s) |  Description  |
| -------------------|-----------------|------------------------------------------------------|
| 10:00am - 10:45am  | Viet Nguyen, MD | [Introduction to FHIR](#introduction-to-fhir)        |
| 10:50am - 1:00pm   | Viet Nguyen, MD | [ClinFHIR Tutorial](#clinfhir-tutorial)          |
| 1:00pm - 2:00pm    | &nbsp; |   Lunch Provided!     |
| 2:00pm - 2:35pm    | Viet Nguyen, MD <br /> Maggie Dorr | [FHIR API Tutorial](#fhir-api-tutorial) |
| 2:45pm - 5:00pm    | Viet Nguyen, MD <br /> Maggie Dorr | Track 1: [FHIR API Tutorial - Part 2](#track-1-fhir-api-tutorial---part-2) |
| 2:45pm - 5:00pm    | Piotr Mankowski | Track 2: [SMART on FHIR Tutorial](track-2-smart-on-fhir-tutorial) |
| 2:45pm - 5:00pm    | Pascal Brandt | Track 3: [CDS Hooks Tutorial](track-3-cds-hooks-tutorial) |

# General Prerequisites
- [ ] Create a public GitHub account if you do not have one by going to www.github.com and clicking the `Sign up for Github` button.

- [ ] Create an account for the HSPC Sandbox by going to https://sandbox.hspconsortium.org/#/start and clicking the `Sign Up` button.

- [ ] Install a text editor for viewing and editing code. Some options:
    * [VS Code](https://code.visualstudio.com/)
    * [Sublime](https://www.sublimetext.com/)
    * [Atom](https://atom.io/)

- [ ] Install Git if you don't have it. Check out the [Git book install guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and the [download page](https://git-scm.com/downloads)
    
    **Note: if you're unfamiliar with git or Github, check these out:**
    - [Github Guides - Hello World](https://guides.github.com/activities/hello-world/)
    - [Github Bootcamp](https://help.github.com/categories/bootcamp/)
    - [Getting Started - Git Book](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

- [ ] Install [Anaconda (Python 3.6 Version)](https://docs.anaconda.com/anaconda/install/)

# Tutorial Descriptions

---
*10:00am - 10:45am*
## Introduction to FHIR

### Learning objectives
- Participants will locate the FHIR specification and navigate between versions of FHIR
- Participants will demonstrate understanding in the five levels of FHIR architecture

--- 
*10:50am - 1:00pm*

## ClinFHIR Tutorial

### Learning objectives
- Participants will read the FHIR resource definitions and apply this understanding to creation of FHIR resource instances using the clinfhir.com FHIR client
- Participants will demonstrate the use of basic FHIR operations using the clinfhir.com FHIR client
- Participants will demonstrate the FHIR server data, terminology and conformance capabilities

--- 
*2:00pm - 2:40pm*
## FHIR API Tutorial

https://github.com/uw-fhir/fhir-api-tutorial

### Learning objectives


---
*2:50pm - 5:00pm*


## Track 1: FHIR API Tutorial Part 2
This tutorial will build on the previous session and allow participants to either (1) build a BMI Calculator 
https://github.com/uw-fhir/fhir-api-tutorial

### Learning objectives
- Participants will identify and create the FHIR resources require for a given health calculator
- Participants will demonstrate the use of the FHIR APIs search a FHIR server and retrieve resources

## Track 2: SMART on FHIR Tutorial
In this tutorial, we will demonstrate how to build a SMART on FHIR web application and launch this application the HSPC Sandbox.

https://github.com/uw-fhir/smart-on-fhir-tutorial

### Learning objectives
- Participants will demonstrate an understanding of the SMART on FHIR Authorization Sequence
- Participants will demonstrate an understanding of using SMART on FHIR  
- Participants will register and launch a client-SMART on FHIR application on the HSPC Sandbox

## Track 3: CDS Hooks Tutorial
In this tutorial, we will work on a simple Clinical Decision Support tool that uses the CDS Hooks standard 
to provide clinical decision support in response to specific triggers in the EHR.

https://github.com/uw-fhir/cds-services-tutorial

### Learning objectives
- Participants will understand the motivations behind the nascent CDSHooks standard and the role it can play in EHR clinical decision support
- Participants will create a simple CDS service and demonstrate it's use with the CDS Hooks Sandbox

### Additional Prerequisites
- [ ] Install [Node.js](https://nodejs.org/en/download/)

---

# Useful Resources for Further Exploration

## Tutorials

### Cerner
- https://github.com/cerner/bunsen-tutorial
- https://github.com/cerner/smart-on-fhir-tutorial
- https://github.com/cerner/cds-services-tutorial

### FHIR Crucible
- https://github.com/fhir-crucible

### UW
- https://psbrandt.io/fhir/
- https://github.com/uwbhi/CDS-Hooks-Tutorial/blob/master/tutorial.md

### HSPC
- https://healthservices.atlassian.net/wiki/spaces/HSPC/pages/39911491/CDS+Hooks+Walk-through
- https://healthservices.atlassian.net/wiki/spaces/HSPC/pages/25133059/Java+Client+Tutorial+Profiles+and+Resource+Extensions
- https://healthservices.atlassian.net/wiki/spaces/HSPC/pages/15171628/OAuth2+Authorization+Walk-through


## Sandboxes & App Galleries
- http://docs.smarthealthit.org/sandbox/
- https://apps.smarthealthit.org/
- https://sandbox.hspconsortium.org/
- https://gallery.hspconsortium.org/
- https://code.cerner.com/en/apps
- https://fhir.cerner.com/millennium/dstu2/#open-sandbox
- https://developer.allscripts.com/content/fhir/content/FHIR_Sandboxes/
- https://open.epic.com/AppExchange/Sandbox
- https://apporchard.epic.com/ (requires applying for login)


