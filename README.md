<h1>Security Audit on Botium Toys (fake enterprise) </h1>

<h2>Description</h2>
The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. It was reviewed the assets Botium Toys has and the controls and compliance practices they have in place.

<br />

<h2>Objectives</h2>
Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices that need to be implemented to  improve Botium Toys’ security posture

<h2>Utilities Used</h2>

- <b>Controls and Compliance Checklist</b> 

<h2>Details:</h2>

<b>Current assets:</b> 
<br /> 
Assets managed by the IT Department include: 
- On-premises equipment for in-office business needs  
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring 
<br /> 

<b>Risk assessment:</b> 
Risk description: Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. 
<br/> 
Control best practices: The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.
<br/> 
Risk score: On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

<b>Scenario:</b> 
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

- Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
- Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database. 
- Access controls pertaining to least privilege and separation of duties have not been implemented.
- The IT department has ensured availability and integrated controls to ensure data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
- Antivirus software is installed and monitored regularly by the IT department. 
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does not have backups of critical data. 
- The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
- Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters). 
- There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
- While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
- The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.

<h2>Controls and Compliance Assessment:</h2>

![1](https://github.com/user-attachments/assets/2d2730d3-fef5-4e4a-a103-0fb16c3f1f89)
<br />
![2](https://github.com/user-attachments/assets/b23e06b9-5f4b-4af0-bc8e-fb37b0419a59)
<br />
![3](https://github.com/user-attachments/assets/7721e972-7400-4b7c-9fa4-8a75cbac9f9b)
<br />
![4](https://github.com/user-attachments/assets/44ad44e6-7035-47be-bf76-d30afeab719e)
<br />

<h2>Recommendations:</h2>
Considering the current Botium Toys security posture, it’s suggested implementing
least privilege, disaster recovery plans and separation of duties as administrative controls. For
technical controls, it’s suggested implementing a backup system based on a backup policy and
also intrusion detection systems. Besides that, data encryption and a password management
system (which would force users to follow the password policies) are also suggested once they
would contribute with data confidentiality and integrity. Once legacy systems are not
monitored, and maintenance and intervention is not done considering a schedule, implementing it would also be a plus. Implementing a data classification and inventory system
would also help and reduce attack surface and data breach risks. Except for the areas
mentioned, the company is securely compliant, and only constant follow-up should be taken.
<!--
 ```diff
