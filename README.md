_Contents:_

[NH EASY] | [Libraries] | 

# NH EASY 
NH EASY, is New Hampshire DHHS's IE&E self-service portal, designed and developed by Deloitte. This repository contains the code base for one of NH EASY's core module - Application for Services. Its over 45 distinct pages allow for functionality to be nuanced and compartmentalized enough to respond to user desires and provide an enhanced user experience. 

The application is developed using open software architecture principles and uses Angular framework, Type Script, HTML, and SASS stylesheets. The application implements a secure interface and authorization-based page flow. The application is intuitive, user friendly, and 508 complaint. Additionally, the application uses a cache management strategy for optimizing requests with the Business APIs. 


# Libraries
* NGXS : NGXS is used for state management
* Swimlane NGX Datable : Used for presenting large & complex data in a tabular format which has features like sorting, filtering, etc.
* Bootstrap (V-4) : Mobile first responsive design, to design the web-site in Mobile, tablet and desktops.
* Date FNS : This is a modern Java Script utility/Library for support to Dates
* Font Awesome: This library is used for icons.
* Ngx Mask : For masking SSN, Phone Numbers, Dates etc
* Ramda : A practical functional library for JavaScript programmers. This project is build around this library.
* Ramda Adjunct : Another JS library, similar to Ramda, but this has more options/features than the Ramda
* RxJs : Reactive extensions for JS

#  Features
*  The application has a responsive user interface with a modern look and feel across browsers and devices (including mobile)
*  The application is fully 508 compliant
*  Streamlined questions in the application entry module with user friendly forms
*  Code follows stringent security standards based on the National Institute of Standards and Technology (NIST) benchmark 
*  Electronic verifications through integration with federal interfaces like SSA, VCI, VLP
*  Integration with third party services like Trumpia for text messaging, Experian for Identity proofing, phone, email and physical address validation.

 
# Functions 
## Client
* Applications : Assist individuals applying for benefits through New Hampshire’s self-service portal 
* Appointments : Clients are able view, cancel, and reschedule appointments in their NH EASY account online
* Choose Health Plans :
* Benefit Status : Clients can view their Benefit status
* NHEP work activity Hours: Clients can now access information regarding their NHEP work program through their NH EASY account
* Screening: Quick screening tool which lets the client check if they might be eligible for benefits before completing the full application
* Record track Program Participation Details
* Authentication and Authorization: NH EASY uses the state's Identity and Access management APIs for authentication and authorization.
* Document Uploads : Allows clients to upload required documents for verifications
* Email and Text Reminders: NH EASY has added reminders through additional channels such as text messages and emails to help increase awareness. Users have the optional ability to opt in and out at any point
* Live Chat : Allows clients to interact real-time with state representatives to offer assistance
* Real time processing: NH EASY is integrated with the Real time Processing APIs to process MAGI or Family Planning applications in real time
*  Nudges:There are context-specific nudges throughout NH EASY to provide additional reminders and help for different scenarios. Banners across the top of the user’s dashboard homepage when they log in.


## Provider
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

 





