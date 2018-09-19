# Tutorials Plan

## Prerequesites
**Install these on your system before the tutorials!**

- Anaconda: https://docs.anaconda.com/anaconda/install/
- A public github account: got to www.github.com and create an account if you don't already have one!
- 

### Test Your System

### Troubleshooting
If you are getting an error saying Anaconda can't find the `fhirclient` module, you have to make sure you're installing the package in a way that the jupyter environment can load it. If doing a global `pip install fhirclient` does not work:

1. Open your `Anaconda Prompt`. 
2. Type `jupyter console`.
3. Paste the following code to make sure fhirclient (or any other missing packages) are installed where Anaconda can access it.

        ```python
        # Install a pip package in the current Jupyter kernel
        import sys
        !{sys.executable} -m pip install
        ```
        (see https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/ for more info)

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

#### Based On
- Framingham Risk Calculator Jupyter Notebook



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

#### Based On
- https://github.com/cerner/smart-on-fhir-tutorial


### Level Three
A CDS Service that interacts with the HSPC Sandbox / CDS Hooks Sandbox to provide clinical decision support / public health advisories / anything that might be relevant to the subject given some triggers. 

** Intro to CDS Hooks
** Intro to possible triggers

#### Teaching Objectives
- CDS Hooks Concepts, API, & Interaction Pattern
- Integration into real clinical scenarios - right time, right place, right advice
- Demonstration of flexiblility and capabilities of CDS Hooks
  
#### Required Knowledge

## Resources

### Tutorials

#### Cerner
- https://github.com/cerner/bunsen-tutorial
- https://github.com/cerner/smart-on-fhir-tutorial
- https://github.com/cerner/cds-services-tutorial

#### FHIR Crucible
- https://github.com/fhir-crucible

#### UW
- https://psbrandt.io/fhir/
- https://github.com/uwbhi/CDS-Hooks-Tutorial/blob/master/tutorial.md

#### HSPC
- https://healthservices.atlassian.net/wiki/spaces/HSPC/pages/39911491/CDS+Hooks+Walk-through
- https://healthservices.atlassian.net/wiki/spaces/HSPC/pages/25133059/Java+Client+Tutorial+Profiles+and+Resource+Extensions
- https://healthservices.atlassian.net/wiki/spaces/HSPC/pages/15171628/OAuth2+Authorization+Walk-through


### Sandboxes & App Galleries
- http://docs.smarthealthit.org/sandbox/
- https://apps.smarthealthit.org/
- https://sandbox.hspconsortium.org/
- https://gallery.hspconsortium.org/

- https://code.cerner.com/en/apps
- https://fhir.cerner.com/millennium/dstu2/#open-sandbox

- https://developer.allscripts.com/content/fhir/content/FHIR_Sandboxes/

- https://open.epic.com/AppExchange/Sandbox
- https://apporchard.epic.com/ (requires applying for login)


