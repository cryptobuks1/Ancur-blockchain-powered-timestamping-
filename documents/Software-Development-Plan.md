## Ancur Software Development Plan  

### Table of Contents
* 4.1 Plan Introduction
* 4.1.1 Project Deliverables
* 4.2 Project Resources
* 4.2.1 Hardware Resources
* 4.2.2 Software Resources
* 4.3 Project Organization
* 4.4 Project Schedule
* 4.4.1 PERT / GANTT Chart
* 4.4.2 Task / Resource Table
* 4.4.3 Class Schedule

### 4.1 Plan Introduction  
This Software Development Plan provides the detail of the planned development for the Ancur web application that provides an application allowing users to validate documents on the Bitcoin and Ethereum blockchains.  

Ancur uses the Stampery API to embed hashes associated with documents into the blockchain - the process is called *stamping*. This process provides the user with a *receipt* for the blockchain being used and each *receipt* has all the necessary data for proving the validity of the stamped document - *id*, *token*, *bitcoin receipt*, *ethereum receipt*, *timestamp*, *hash*, ... . Ancur is an application that utilizes blockchain technology to provide users with a secure way to validate their documents on the Bitcoin and Ethereum blockchains.

#### 4.1.1 Project Deliverables  
* Project Proposal - *week 2*
    * This document provides a description and justification of the application.

### 4.2 Project Resources  
#### 4.2.1 Hardware Resources
**Development Machine**
An Apple laptop is used for the development of the application with the following attributes;
* MacBook Pro (13-inch, Late 2013)
* 2.6 GHz Intel Core i5
* 8 GB RAM
**Online Application Host**
A website will be the platform used for the application. This is where the features will be available to the users.
* HTML 5 Support
* Chrome, Safari, Firefox, Edge(Internet Explorer)  

#### 4.2.2 Software Resources
**Text Editor**
* Atom v1.23.3
**Interpreter and Executer**
* Node v8.9.4
**Version Control**
* Git v2.11.0
**Third Party Software**
* [Stampery API](https://stampery.com/)

### 4.3 Project Organization

### 4.4 Project Schedule
* "Stamping" feature implementation  <!-- TODO -->
    * Use the Stampery API
    * Provide user with downloadable document including their stamped document's *id*, *token*, *receipts*,...
* Prove stamped document feature implementation
    * Use the Stampery API again
    * Allow user to prove their document has been stamped using their stamped document's id.
*
#### 4.4.1 PERT / GANTT Chart
#### 4.4.2 Task / Resource Table
#### 4.4.3 Class Schedule