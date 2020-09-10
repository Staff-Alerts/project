# Staff Alerts - Proposal

## Recent updates

* [Week 1](.../updates/week1.md)

## Background

The Staff Alerts service will provide a centralised facility which can rapidly inform Environment Agency (EA) staff of incidents via text message. These alerts will protect the safety of staff within the organisation and limit loss of staff productivity. Key communications are time critical to business delivery, thus consistent and rapid delivery is fundamental.  

The intention is for this service to eventually replace the existing EA Text Alerts service which is hard to maintain and manage. The currently in progress "Defra Single Group Text Alert Service" project does **not** intend to replace the existing EA Text Alerts service.


## Goals

* To build a service to notify staff about business disruptions affecting the organisations sites and the 16 operational areas
* To create a quick, user-friendly and low-cost service
* To allow staff to “self-manage” their details
* To design a service that can be re-used by others


## Objectives

1. Identify and implement a way to securely obtain, maintain and store the necessary staff data across the organisation - following GDPR requirements

1. Identify and implement a way to allow staff to securely register, maintain and remove their own data from the service - following GDPR requirements

1. Create an accessible and intuitive internal interface that:
    1. has a secure user login mechanism
    1. allows for the creation of messages
    1. allows for "approval" of messages before sending
    1. allows for the issuing of messages
    1. allows for basic staff data maintenance
    1. allows for the creation and maintenance of message templates
    1. provides a simple message history
    1. provides a simple contact history
    1. provides a simple audit log

1. Identify and implement a way to send text messages to relevant staff using GOV.UK Notify

1. Identify and implement a way to monitor the success of the text messages issued

1. Identify and implement a way to remove duplicate messages before they are issued

1. Fully document the approach, design and implementation of the Staff Alerts service for handover to Internal Digital Services


## Benefits

* Provides a better service for users with lower overheads for future transition to Internal Digital Services
* We can better meet the user needs we have seen and have had through feedback
* Substantially reduces the maintenance overhead from the Extremal Digital Services team
* Lower cost (current contract ~ around £40k)
* Ability to re-use components from XWS (NeXt Warning System) development
* Ability to open source our work for re-use by Defra or others without restriction

## Timeline

* 14 Sep - 25 Sep: Disco/Planning/UR/Backlog refinement - 2 weeks
* 28 Sep - 09 Oct: Alpha build - 2 weeks
* 12 Oct - 16 Oct: Iteration and user testing - 1 week
* 19 Oct - 23 Oct: Iteration and user testing - 1 week
* 26 Oct - 30 Oct: Contingency week
* November: Initial release


## Team

* Liz Hills – Delivery Manager
* Polly Sait – Product Manager (for alpha phase)
* Dave Stone – Lead developer
* Ray Hanson – Developer / Tester
* Simon Nebesnuick – Service Design / Scrum Master

### Subject Matter Experts

* Internal Digital Services - Sharon Sawyer
* Incident Communication Service - Steph Turner/Lisa Matthews 
* Business Continuity Incident Management – Chris Strong
