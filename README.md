_Contents:_

[NH EASY](#nh-easy) | [Libraries](#libraries)  | [Features](#features) | [Functions](#functions) |

# NH EASY 
NH EASY, is New Hampshire DHHS's IE&E self-service portal, designed and developed by Deloitte working with State of NH. This repository contains the code base for one of NH EASY's core modules - Application for Services. 

Note: NH EASY also has code for other functions like Gateway toAccount Management, Recertification, Change Reporting, Reapply that has not been provided in this repository.

The application is developed using open software architecture principles and uses Angular framework, Type Script, HTML, and SASS stylesheets. The application implements a secure interface and authorization-based page flow.Its over 45 distinct pages allow for functionality to be nuanced and compartmentalized enough to respond to user desires and provide an enhanced user experience.  The application is intuitive, user friendly, and 508 complaint. Additionally, the application uses a cache management strategy for optimizing requests with the Business APIs. 


# Libraries
* NGXS : NGXS is used for state management
* Swimlane NGX Datable : Used for presenting large & complex data in a tabular format which has features like sorting, filtering, etc.
* Bootstrap (V-4) : Used for mobile first responsive design, to build web-site for Mobile, tablet and desktops.
* Date FNS : Modern Java Script utility/library for Date functions.
* Font Awesome: Library used for Icons.
* Ngx Mask : For masking sensitive data like SSN, Phone Numbers, etc.
* Ramda and Ramda Adjunct : Library of Javascript utility functions
* RxJs : Reactive extensions for Javascript to compose asynchronous or callback based code

#  Features
*  The application has a responsive user interface with a modern look and feel across browsers and devices (including mobile)
*  The application is fully 508 compliant
*  Streamlined questions in the application entry module with user friendly forms
*  Code follows stringent security standards based on the National Institute of Standards and Technology (NIST) benchmark 
*  Electronic verifications through integration with federal interfaces like  SSA, VCI, VLP
*  Integration with third party services like Trumpia for text messaging, Experian for Identity proofing, phone, email and physical address validation.
*  Application has a comprehensive error-handling framework enabling users throughout the system to see business messages that make sense to a client. The error-handling framework is built to allow for auto-recording of errors throughout the system to enable troubleshooting during operations and maintenance procedures.

 
# Functions 
## Client
* Applications : Assist individuals applying for benefits through New Hampshire’s self-service portal 
* Real time processing: NH EASY is integrated with the Real time Processing APIs to process MAGI or Family Planning applications in real time
*  Nudges:There are context-specific nudges throughout NH EASY to provide additional reminders and help for different scenarios. Banners across the top of the user’s dashboard homepage when they log in.
### Additional Functions Deloitte solution offers as part of the IE&E solution
* Appointments : Clients are able view, cancel, and reschedule appointments in their NH EASY account online - gw
* Benefit Status : Clients can view their Benefit status - gw
* NHEP work activity Hours: Clients can now access information regarding their NHEP work program through their NH EASY account - gw
* Screening: Quick screening tool which lets the client check if they might be eligible for benefits before completing the full application - gw
* Record track Program Participation Details: - gw
* Authentication and Authorization: NH EASY uses the state's Identity and Access management APIs for authentication and authorization.- gw
* Document Uploads : Allows clients to upload required documents for verificationsv- gw
* Email and Text Reminders: NH EASY has added reminders through additional channels such as text messages and emails to help increase awareness. Users have the optional ability to opt in and out at any point - gw
* Live Chat : Allows clients to interact real-time with state representatives to offer assistancev- gw



## Provider- gw
* Access to portal functions based on pre-determined roles. Ability to add / edit user profiles based on roles
* LTSS Dashboards: LTSS dashboard is a one stop shop for creating, submitting and tracking assessments electronically via NH EASY 
* CFI Dashboards: CFI dashboard will be used by Case Management Agency (CMA) Supervisors and Case Managers to track all ongoing activities related to managing plans and services  
* Manage Cases: Manage Cases screen lists all the clients that have given the provider organization full access to their NH EASY case information
* Apply for Assistance
  * Assist individuals applying for benefits through New Hampshire’s self-service portal. 
  * Enter information for all records throughout the application for the individual
* Search Applications
  * Search for applications the provider has submitted for individuals via different criteria 
  * Resume individual’s applications the provider has started, but not submitted
* WIC Dashboard : Enables providers to track and manage the referrals associated with their organization
* User Management: Lists details of everyone who has NH EASY access within an organization

 





