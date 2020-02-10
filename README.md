This repository acts as a knowledge base related to the RADON methodology, containing an overview and links of the RADON architecture, tools, actors and methodology.

# Table of Contents
* [RADON Architecture](#radon-architecture)
* [RADON Actors and Stakeholders](#radon-actors-and-stakeholders)
* [RADON Methodology](#radon-methodology)
* [RADON Tools](#radon-tools)

# RADON Architecture

The RADON framework provides a set of components that realize a set of tools, modules and services covering both the design and runtime phases of microservices and serverless-oriented application development and deployment.

## Architecture Diagram

![#radon-architecture](RADON-Architecture.png)


## Architecture Overview

The Architecture Diagram depicts the connections among the RADON components. The design time components interact with each other and with the runtime components in order to design, prototype, deploy and test applications built on serverless FaaS.

In this context a particular role is played by the RADON IDE. This component is be based on [Eclipse Che](#https://www.eclipse.org/che/) and provides a multi-user development environment to access the RADON artifacts. Indeed, as depicted in the Architecture diagram, the RADON IDE interacts also with the Template Library. This is done to access the reusable base types, abstractions and TOSCA extensions and make them available to the RADON tools (see Section 2.2), that require them to model a RADON application. Moreover, the RADON IDE  acts as the front-end of the RADON methodology, by enabling users to invoke RADON tools supporting both the design and runtime phases of application development.

# RADON Actors and Stakeholders

RADON intends to deliver a DevOps-inspired methodology. On that basis, RADON proposes to identify a few reference DevOps actors. A RADON actor defines a role -- not a single human or software -- therefore the same person can potentially act as multiple RADON actors and the same role could be split across multiple actors. The RADON actors are as follows:

* Software Designer: this actor is responsible of the application architecture and data lifecycle design.
* Software Developer (Dev): responsible for business logic coding and testing.
* Operations Engineer (Ops): responsible for delivery on the infrastructure and infrastructure testing.
* QoS Engineer: responsibility for ensuring performance/reliability/security/privacy/access control properties of the application,
* Release Manager: team leader that authorizes major changes and their release to production.

For more information on RADON actors, please refer to the deliverable document [D2.1 - Initial Requirements and Baselines](http://radon-h2020.eu/wp-content/uploads/2019/07/D2.1-Initial-requirements-and-baselines.pdf)

# RADON Methodology

The RADON DevOps methodology consolidates the user workflow for using RADON tools and the DevOps paradigm for software delivery and evolution. In the context of a DevOps lifecycle, we have defined several workflows as abstractions to organize and present the possible interactions of the different tools within the RADON framework and with the identified actors. DevOps actors as described above are fundamental to reason about the existing development and operations roles and re-assign them for the continuous delivery of software in the context of RADON. 

Furthermore, the defined workflows help understand and further refine the application development lifecycle with the RADON framework, considered as an iterative process involving Design, Development (Deployment) and Runtime.  The defined workflows are described below.
 


## Methodology Overview

## Workflows

### Verification

Verification of the application models. Involved tools are Graphical Modelling tool, Constraint Definition Language and the Verification Tool.

### Decompositon

Decomposition of functionality in microservices/FaaS. Involved tools are Graphical Modelling tool and Decomposition tool, and the Template Library.


### Defect Prediction

Defect Prediction of the infrastructure code. Involved tools are the IDE and Defect Prediction tool.

### Continuous Testing

Continuous Testing of the performance and integration of components. Involved tools are the IDE, Continuous Testing tool and Monitoring tool.

### CI/CD

CI/CD to automate the deployment of a RADON application. Involved tools are the Orchestrator, CI/CD pipeline, and Monitoring tool.

### Monitoring

Monitoring of simple metrics to provide feedback for refining the deployment. Involved tools are the Orchestrator and Monitoring tool.

More information about RADON workflows can be found at the deliverable document 
[DELIVERABLE 2.3 – ARCHITECTURE & INTEGRATION PLAN I](http://radon-h2020.eu/wp-content/uploads/2019/11/D2-3_Architecture-and-integration-plan-I.pdf)

# RADON Tools

## Defect Prediction Tool
### Overview
### Link 
### Sequence and Activity Diagrams
### Move to RADON Repository?

## Decomposition Tool
### Overview
### Link 
### Sequence and Activity Diagrams

## CDL and Verification Tool
### Overview
### Link 
### Sequence and Activity Diagrams

## Continuous Testing Tool
### Overview
### Link 
### Sequence and Activity Diagrams

## Orchestrator
### Overview
### Link 
### Sequence and Activity Diagrams

## Data Pipeline Plugins
### Overview
### Link 
### Sequence and Activity Diagrams

## Integrated Development Environment
### Overview
### Link 
### Sequence and Activity Diagrams

## Template Library
### Overview
### Link 
### Sequence and Activity Diagrams

## Graphical Modeling Tool (winery extension)
### Overview
### Link 
### Sequence and Activity Diagrams

## Monitoring System
### Overview
### Link 
### Sequence and Activity Diagrams

