# Software Requirement Specification 

## Overview

The Software Requirements Specification (SRS) document shows the functional & non-functional requirements for our Vehicle Inventory Webpage (CarChoice). Our webpage will be built based on the requirements outlined below. This document will help us stay on track and reduce scope creep. This can also serve as a part of documentation which will help future developers who would become a part of this project to gain more insights on the project's status.

# Software Requirements

The software requirements are organized into two clear categories: **Functional Requirements** and **Non-Functional Requirements**. Each category is presented in a table format for easy understanding. The tables include unique IDs and brief descriptions of each requirement. This setup makes it simple to see what the system can do (functional requirements) and how well it should perform (non-functional requirements). This approach ensures the requirements are clear, align with the project goals, and meet user needs effectively.

## Functional Requirements


### Featured Cars
| ID  | Requirement |
| :--:| :------------------------------------------------------------------------------------------------------------------------------------------- |
| FR1 | The system shall display a list of featured cars on the homepage, dynamically updating based on popularity and user preferences. |
| FR2 | The system shall provide a detailed view for each featured car, including specifications, images. |
| FR3 | The system shall allow the specified persons to manually select and mark certain cars as "Featured Cars." |
| FR4 | The system shall display featured cars with a special badge or label to highlight them to users. |
| FR5 | The system shall allow users to compare featured cars side-by-side. |
| FR6 | The system shall provide user to view new cars in Featured Cars tab. |

### Compare Cars
| ID  | Requirement |
| :--:| :------------------------------------------------------------------------------------------------------------------------------------------- |
| FR7 | The system shall display the details for both cars after selection, including Model, Year, Mileage, Price, Horsepower, and Transmission. |
| FR8 | The system shall ensure that users can compare the features of car1 and car2 side-by-side. |
| FR9 | The system shall allow users to modify the selected cars and update the comparison results accordingly. |
| FR10 | The system shall update the comparison results dynamically when the user selects different cars. |
| FR11 | The system shall allow users to refresh the selected cars and start a new comparison. |

### Brands
| ID  | Requirement |
| :--:| :------------------------------------------------------------------------------------------------------------------------------------------- |
| FR12 | The system shall display detailed information about a brand, such as its image, year of establishment, country of origin, and models. |
| FR13 | The system shall enable users to view all brands available in the database. |
| FR14 | The system shall provide search functionality for users to find specific brands based on their interest. |
| FR15 | The system shall allow users to mark specific brands as favorites for quick access in the future. |
| FR16 | The system shall support filtering of brands by country of origin. |

### Search Feature
| ID  | Requirement |
| :--:| :------------------------------------------------------------------------------------------------------------------------------------------- |
| FR17 | The system shall provide options for users to select a country to filter out the results. |
| FR18 | The system shall display only cars from the selected country when a user filters out the result. |
| FR19 | The system shall allow users to select a specific car brand. |
| FR20 | The system shall allow users to select a specific car model. |
| FR21 | The system shall allow users to filter cars based on the year of manufacture. |
		

### New Cars
| ID  | Requirement |
| :--:| :------------------------------------------------------------------------------------------------------------------------------------------- |
| FR22 | The system shall show top 3 new trending cars upon clicking on new cars tab.|
| FR23 | The system shall display an image of the car. |
| FR24 | The system shall display the car brand and car name. |
| FR25 | The system shall contain information about those new cars. |
| FR26 | The system shall cycle through these three cars, showing one at a time. Each car's details shall be displayed for a few seconds before transitioning to the next, and this cycle shall repeat. |

## Non-Functional Requirements

### Performance
| ID  | Requirement |
| :--:| :------------------------------------------------------------------------------------------------------------------------------------------- |
| NFR1 | The system shall ensure that the featured cars section loads quickly for a better user experience. |
| NFR2 | The system shall be able to handle many users at a time without any performance degradation. |
| NFR3 | The system shall provide consistent performance, ensuring all brand-related operations are smooth and efficient. |
| NFR4 | The transition between top car displays shall occur smoothly, without delays or noticeable lags, ensuring a good user experience. |
| NFR5 | When user clicks on Country, Brand or Model the options to select from shall be displayed without any delay. |


### Usability
| ID  | Requirement |
| :--:| :------------------------------------------------------------------------------------------------------------------------------------------- |
| NFR6 | The system shall display the featured cars section correctly on various devices, including desktops, tablets, and smartphones. |
| NFR7 | The system shall provide a user-friendly interface for managing brand details. |
| NFR8 | The system shall be compatible with the latest versions of major web browsers (e.g., Chrome, Firefox, Safari), including desktops, tablets, and smartphones. |
| NFR9 | The search and filter interface shall be user-friendly, with clear labels and an easily interpretable design to make it easy for users to select and apply filters. |
| NFR10 | The text size of the options in search bar should be big enough for most of the people to read. |
| NFR11 | The system shall display the featured cars section correctly on various devices, including desktops, tablets, and smartphones. |


### Scalability
| ID  | Requirement |
| :--:| :------------------------------------------------------------------------------------------------------------------------------------------- |
| NFR12 | The system shall be scalable to support the addition of more car brands, models, and years. |
| NFR13 | The system shall be capable of handling a large number of featured cars in the list without affecting performance. |
| NFR14 | The system shall handle an increase in the number of car images and details without performance degradation. |
| NFR15 | The search functionality shall safely search from our database only and not provide results from anywhere else. |


### Reliability
| ID  | Requirement |
| :--:| :------------------------------------------------------------------------------------------------------------------------------------------- |
| NFR16 | The system shall maintain data integrity, ensuring that the car details displayed are accurate and up-to-date. |
| NFR17 | The system shall retrieve and display brand data accurately for the entries in the database. |
| NFR18 | The feature shall function consistently across different browsers and devices, with no errors in image or data rendering. |
| NFR19 | The system shall ensure data integrity by preventing duplicate entries of brand names. |
| NFR20 | The filtering operations (e.g., by country, brand, model, or year) shall execute and show results quickly, regardless of the size of the dataset. |


### Maintainability
| ID  | Requirement |
| :--:| :------------------------------------------------------------------------------------------------------------------------------------------- |
| NFR21 | The system shall update the featured cars list daily based on predefined business rules and user behavior analytics. |
| NFR22 | The system shall ensure that the comparison data is accurate and updated regularly to reflect the latest car model specifications. |
| NFR23 | The system shall maintain data consistency when multiple users interact with featured cars. | 
| NFR24 | The system shall ensure that all updates and changes to brand, featured cars, and comparison data are manageable and efficient. | 
| NFR25 | The feature's codebase shall be modular and well-documented, making it easy to update or extend in the future. | 

# Change management plan

### How will you train people to use it?

To ensure users have a smooth experience with our platform, we will provide documentation explaining each feature, such as how to search, filter, and compare cars effectively. To enhance user experience further, we will conduct usability testing by inviting real users to interact with our website. Through this process, we will identify common  questions and challenges faced by users. Based on these insights, we will compile a list of frequently asked questions (FAQs) and provide clear answers directly on the platform. In addition to this a dedicated space will be created where users can email their questions or concerns to us. To encourage continuous improvement, we will implement a feedback system where users can share their opinions, suggestions, or issues encountered while using the platform. All feedback will be carefully reviewed, and any good suggestions will be incorporated into future updates and enhancements.

### How will you ensure it integrates within their ecosystem / software?

We have used modular approach to build our webpage, for example if there is a website which has cars data and wants to add the comparison feature into their site then they can intigrate the compare feature easily as it is present in a separate file. Our code is also easily readable and understandable so anyone can easily seperate the code for specific feature and add it to theirs, for example the search functionality. Users can take up only this specific feature and add it to their codes. To further assist teams, we offer Zoom-based Knowledge Transfer (KT) sessions where we walk them through the system architecture, individual modules, and functionalities while addressing any questions to ensure smooth integration. This modular design, combined with detailed documentation and dedicated support, enabling teams to enhance their platforms with ease.


### How will you ensure that it any discovered issues are resolved?

Using feedback mechanism that allows users to report issues or share feedback directly with us. Upon receiving a notification, our team will review the reported issue to verify its legitimacy. Once validated, we address the problem by making the necessary changes to the existing code, followed by redeploying the updated system. To ensure the issue is fully resolved, we conduct thorough user acceptance testing from our end. After confirming the resolution, we notify the user via email, informing them that the issue has been successfully addressed. This process ensures a responsive and user-focused approach to maintaining and improving our platform.



# Traceability links

## Use Case Diagram Traceability

| Artifact ID    | Artifact Name        | Requirement ID             |
|----------------|----------------------|----------------------------|
| UseCase1       | Display Featured Cars | FR1, FR2, FR4              |
| UseCase1       | Manage Featured Cars  | FR3, FR5                   |
| UseCase2       | Compare Cars          | FR7, FR8, FR9, FR10, FR11  |
| UseCase3       | Manage Brands         | FR12, FR13, FR14, FR15, FR16 |
| UseCase4       | Search Cars           | FR17, FR18, FR19, FR20, FR21 |
| UseCase5       | View New Cars         | FR22, FR23, FR24, FR25, FR26 |



## Activity Diagram Traceability

| Artifact ID                | Artifact Name           | Requirement ID              |
|----------------------------|-------------------------|-----------------------------|
| User Activity Diagram      | Display Featured Cars   | FR1, FR2, NFR6              |
| User Activity Diagram      | Manage Featured Cars    | FR3, FR5, NFR5              |
| User Activity Diagram      | Compare Cars            | FR7, FR8, FR9, FR10, FR11   |
| User Activity Diagram      | Manage Brands           | FR12, FR13, FR14, FR15, NFR7|
| User Activity Diagram      | Search Cars             | FR17, FR18, FR19, FR20, FR21|
| User Activity Diagram      | View New Cars           | FR22, FR23, FR24, FR25, FR26|
| Admin Activity Diagram     | Update Featured Cars    | FR3, FR5, NFR5              |
| Admin Activity Diagram     | Update Brands           | FR12, FR13, FR14, FR15, NFR7|
| Admin Activity Diagram     | Manage Cars             | FR1, FR7, FR8, FR9, FR10, FR11 |
| Admin Activity Diagram     | Update New Cars         | FR22, FR23, FR24, FR25, FR26|



## Class Diagram Traceability

| Artifact Name        | Requirement ID                       |
|----------------------|--------------------------------------|
| User                 | FR1, FR2, FR3, FR5, FR7, FR8, FR9, FR10, FR11, FR12, FR13, FR17, FR18, FR19, FR20, FR21, FR22, FR23, FR24, FR25, FR26, NFR1, NFR5, NFR6, NFR7, NFR9 |
| Admin                | FR3, FR5, FR12, FR13, FR14, FR15, FR16, FR7, FR8, FR9, FR10, FR11, FR22, FR23, FR24, FR25, FR26, NFR5, NFR7, NFR9 |
| Brands               | FR12, FR13, FR14, FR15, FR16, NFR7 |
| Comparison           | FR7, FR8, FR9, FR10, FR11, NFR9 |



# Software Artifacts

This section showcases the key software artifacts for our CarChoice project, such as Use Case, Activity, Class, Object, and Navigation diagrams. These artifacts, available through the provided links, offer visual representations of different system components, from user interactions to overall architecture. They provide stakeholders with a clear and detailed view of the project's design and functionality, ensuring a thorough understanding.

* [User and Vehicle Activity diagram](https://github.com/rohitajala/GVSU-CIS641-NinjaTurtles/blob/main/artifacts/Activity%20Diagrams%20Final.pdf)

* [CRC Card diagram](https://github.com/rohitajala/GVSU-CIS641-NinjaTurtles/blob/main/artifacts/CRC%20Card%20Final.jpeg)

* [Class Specification diagram](https://github.com/rohitajala/GVSU-CIS641-NinjaTurtles/blob/main/artifacts/Class%20Specifications%20Final.docx)

* [Navigation diagram](https://github.com/rohitajala/GVSU-CIS641-NinjaTurtles/blob/main/artifacts/Navigation%20Diagram%20Final.pdf)

* [Sequence and State Machine diagram](https://github.com/rohitajala/GVSU-CIS641-NinjaTurtles/blob/main/artifacts/Sequence%20and%20State%20Machine%20Diagram%20Final.docx)

* [User UseCase diagram](https://github.com/rohitajala/GVSU-CIS641-NinjaTurtles/blob/main/artifacts/Use%20case%20diagrams%20Final.pdf)
