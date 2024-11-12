# Corporate Cybersecurity Assessment utilizing NIST CyberSecurity Framework (CSF) 2.0

## Introduction

For this project I was tasked with analyzing an Organization's ('Oscorp') cybersecurity status and designing a comprehensive cybersecurity program utilizing the [NIST CSF 2.0](https://www.nist.gov/publications/nist-cybersecurity-framework-csf-20) to uplift its security posture. I was given a 'current status' report, much like one that would be compiled after initial investigations and interviews with employees and stakeholders. Using the NIST CSF, I conducted a pass/fail assesment and presented recommendations for improvement. I decided to start with a short presentation to stakeholders to explain the framework and roadmap and ended with presenting them with a comprehensive list of recomendations and procedures to be implemented.

## CSF Core Functions
The CSF Core Functions — GOVERN, IDENTIFY, PROTECT, DETECT, RESPOND, and RECOVER — organize cybersecurity outcomes at their highest level.

| Core Functions  | Description
| --------------- | -----
| ![Screenshot 2024-10-28 134244](https://github.com/user-attachments/assets/c536c78f-b8d2-4988-a1ad-ea1b0222bd41) | The organization’s cybersecurity risk management strategy, expectations, and policy are established, communicated, and monitored.
| ![Screenshot 2024-10-28 134430](https://github.com/user-attachments/assets/bd218bc5-9048-4d91-96fd-77aba367d87b) | The organization’s current cybersecurity risks are understood.
| ![Screenshot 2024-10-28 134438](https://github.com/user-attachments/assets/f6554061-0d01-49e9-91df-b102eb4b8ac7) | Safeguards to manage the organization’s cybersecurity risks are used.
| ![Screenshot 2024-10-28 134447](https://github.com/user-attachments/assets/26e591c9-9ee6-454f-9f5b-37062bec1d0c) | Possible cybersecurity attacks and compromises are found and analyzed.
| ![Screenshot 2024-10-28 134456](https://github.com/user-attachments/assets/bfdf2e21-ced1-4767-8ac6-4ec982b6f5e3) | Actions regarding a detected cybersecurity incident are taken.
| ![Screenshot 2024-10-28 134503](https://github.com/user-attachments/assets/10ef5d64-da8b-41df-a0fe-56acb244fd1c) | Assets and operations affected by a cybersecurity incident are restored.

------
<!-- GOVERN -->
![Screenshot 2024-10-28 135023](https://github.com/user-attachments/assets/a9b93ba7-a2a2-4cdc-954f-8016f3df6e58)

The rigor of an organization’s cybersecurity risk governance and management practices can be categorized according to a table of tiers as outlined in CSF 2.0 Profiles and Tiers. (See Fig. 1)

![image](https://github.com/user-attachments/assets/60704a33-4b7f-4925-8eef-4084d5fa484c)

A Current Profile specifies the Core outcomes that an organization is currently achieving (or attempting to achieve) and characterizes how or to what extent each outcome is being achieved. 

**Oscorp’s current profile is identified as Tier 1: Partial.**
|Tier           | Cybersecurity Risk Governance      | Cybersecurity Risk Management
|---------------|------------------------------------|------------------------------
|Tier 1: Partial | Application of the organizational cybersecurity risk strategy is managed in an ad hoc manner. Prioritization is ad hoc and not formally based on objectives or threat environment. | There is limited awareness of cybersecurity risks at the organizational level. The organization implements cybersecurity risk management on an irregular, case-by-case basis. The organization may not have processes that enable cybersecurity information to be shared within the organization. The organization is generally unaware of the cybersecurity risks associated with its suppliers and the products and services it acquires and uses. 
 
A Target Profile specifies the desired outcomes that an organization has selected and prioritized for achieving its cybersecurity risk management objectives. It considers anticipated changes to the organization’s cybersecurity posture, such as new requirements, new technology adoption, and threat intelligence trends. 

**Target profile for Oscorp: Tier 4:**

|Tier           | Cybersecurity Risk Governance                                                    | Cybersecurity Risk Management
|---------------|----------------------------------------------------------------------------------|------------------------------
|Tier 4: Adaptive | There is an organization-wide approach to managing cybersecurity risks that uses risk-informed policies, processes, and procedures to address potential cybersecurity events. The relationship between cybersecurity risks and organizational objectives is clearly understood and considered when making decisions. Executives monitor cybersecurity risks in the same context as financial and other organizational risks. The organizational budget is based on an understanding of the current and predicted risk environment and risk tolerance. Business units implement executive vision and analyze system-level risks in the context of the organizational risk tolerances. Cybersecurity risk management is part of the organizational culture. It evolves from an awareness of previous activities and continuous awareness of activities on organizational systems and networks. The organization can quickly and efficiently account for changes to business/mission objectives in how risk is approached and communicated. | The organization adapts its cybersecurity practices based on previous and current cybersecurity activities, including lessons learned and predictive indicators. Through a process of continuous improvement that incorporates advanced cybersecurity technologies and practices, the organization actively adapts to a changing technological landscape and responds in a timely and effective manner to evolving, sophisticated threats. The organization uses real-time or near real-time information to understand and consistently act upon the cybersecurity risks associated with its suppliers and the products and services it acquires and uses. Cybersecurity information is constantly shared throughout the organization and with authorized third parties.

At all times the question should be asked whether data is kept *Confidential*, its *Integrity* is upheld, and is readily *Available* and what risks and vulnerabilities present a danger to this ‘[CIA Triad](https://www.nccoe.nist.gov/publication/1800-26/VolA/index.html)’. 

![image](https://github.com/user-attachments/assets/5b8e35de-2c04-4de8-a82c-bb526a3f6f5c)
------
<details close> 
<summary> <h3> Oscorp's Current status report (Click here)</h3> </summary>

**Current Oscorp cybersecurity team:**
- Cyber security analyst: generalist, responds to cyber incidents as they come. Reports
to Oscorp’s IT manager.
- Network engineer: manages the firewalls. Reports to the Network Team Leader.
- Cyber Security Consultant: your new role at Oscorp. You will initially report to the IT
manager.

**Oscorp Current Cyber Security Controls:**
- Organizational governance:
  - CEO has a clear business strategy for the business. However, roles and
responsibilities for cybersecurity haven’t been defined. They’re assigned to
the IT team. There is no cybersecurity strategy.

- Asset Management:
  - The IT team has a spreadsheet with serial numbers of laptops.
  - The spreadsheet includes the model of each machine and details about the
warranty.
  - Oscorp uses Microsoft Office365 and relies exclusively on Software-as-a-
Service applications.
  - All data is in Microsoft Azure cloud
  - The IT team uses a Secure Operating Environment (SOE) to image all their
laptops with the latest Windows desktop version

- Business Continuity and Disaster Recovery:
  - The IT team conducts regular disaster recovery testing
  - The IT team has clear and documented business continuity plans
  - The IT team takes regular backups. Backups get tested periodically

- Vulnerability management:
  - Oscorp have purchased Qualys vulnerability scanner.
  - The IT team uses Qualys on an ad-hoc basis.
  - There is no formal vulnerability management program in place.
  - Large number of high and severe vulnerabilities reported by Qualys

- Risk management:
  - Oscorp has a risk team that performs financial risk activities.
  - There is no technology or cyber risk process at Oscorp.

- Third Party Risk Management:
  - Oscorp doesn’t perform any third-party risk management.
  - Contracts are reviewed by procurement and finance, not IT.

- Identity and Access Management:
  - Oscorp uses Microsoft Active Directory to manage users and groups
  - There is no privileged access management solution in place
  - Admin account password is shared with a few senior members of the IT team
  - Access to resources is granted upon request
  - The organization does not use two-factor authentication for login
  - Complex login passwords are used
  - Employees use a VPN solution to login remotely when required

- Network security:
  - The organization has Palo Alto Next Gen firewalls.
  - The firewalls have been configured by the network
  - The firewalls get audited every year by the network team
  - The firewalls get regular updates
  - The IT team have up to date network diagrams. The diagrams include the
cloud environment.
  - The network is segmented using VLANs.

- Physical Security:
  - Oscorp is a highly secure facility, with state-of-the-art CCTV cameras
everywhere
  - Oscorp takes physical very seriously
  - They do extensive vettng for all their employees
  - The have a 24/7 monitoring for their research labs and physical facilities

- Data Security:
  - Oscorp doesn’t have a DLP soluDon
  - All data resides in Microsoft Azure cloud and Microsoft Office 365
  - Key critical application is a SaaS service from Horizon Labs.

- Policy:
  - There is one generic IT policy in place
  - No formal information security policy
  - There is no data governance policies or information classificaDon

- Cyber Security detection and response:
  - There is no detection or response capability
  - The IT team responds to alerts from the anti-virus (Microsoft Defender)
  - No SIEM in place

- Security Education and Awareness:
  - All employees are required to do an induction web training module. The
module includes basic instructions about cyber security.

  </details>
------

Utilizing CSF Core functions as a guide, an assessment of Oscorp identified many deficiencies. Recommendations will be provided after each subcategory. 

<!--IDENTIFY-->
![Screenshot 2024-10-28 134831](https://github.com/user-attachments/assets/9dc5bda1-08f0-4d90-b806-34621a19553a)

<details close> 
<summary> <h3> Nist Cybersecurity Framework 2.0 Pass/Fail logs (Click here)</h3> </summary>

![image](https://github.com/user-attachments/assets/abe2f966-8146-4dcc-8bf0-0ab1cfa17938)

![image](https://github.com/user-attachments/assets/d61d72d7-d959-4bdd-96e5-e8406551c62f)

![image](https://github.com/user-attachments/assets/1a82cfcd-03d5-45a4-aabb-32cc84fe344a)

  </details>

------
<!--## PROTECT-->
![Screenshot 2024-10-28 134843](https://github.com/user-attachments/assets/eaa0f70b-acb1-43ba-9186-53f4c406875c)

<details close> 
<summary> <h3> Nist Cybersecurity Framework 2.0 Pass/Fail logs (Click here)</h3> </summary>

![image](https://github.com/user-attachments/assets/e8d88aa2-c758-4e8c-94dc-16131907acc4)

![image](https://github.com/user-attachments/assets/1d0c619d-bb1a-44bc-8743-068e1ec212a2)

![image](https://github.com/user-attachments/assets/eb06a12c-7da3-49b0-ab4d-e041b5deaeb7)

![image](https://github.com/user-attachments/assets/ec5b3c57-4912-4893-9567-721c7a6d0332)

![image](https://github.com/user-attachments/assets/5e11a6ef-f0f3-4b76-9131-59c7dd4ad189)


  </details>

------
<!--## DETECT-->
![Screenshot 2024-10-28 134853](https://github.com/user-attachments/assets/2a5d2bd2-ba9b-4cff-84c2-840f73c4633b)

<details close> 
<summary> <h3> Nist Cybersecurity Framework 2.0 Pass/Fail logs (Click here)</h3> </summary>

![image](https://github.com/user-attachments/assets/4dd81dfd-3692-43ef-997d-1e9c8be15291)

![image](https://github.com/user-attachments/assets/acedecf0-5d76-4595-8b45-9f850487c8b0)

![image](https://github.com/user-attachments/assets/e3146487-584a-4257-8480-27ebc54e86cd)

  </details>

------
<!-- RESPOND-->
![Screenshot 2024-10-28 134902](https://github.com/user-attachments/assets/0e5fa430-0cea-4d22-be43-912381a82917)

<details close> 
<summary> <h3> Nist Cybersecurity Framework 2.0 Pass/Fail logs (Click here)</h3> </summary>

![image](https://github.com/user-attachments/assets/d81c80c1-9de2-4f9d-a723-75c9d880ed19)

![image](https://github.com/user-attachments/assets/b187af42-b8c7-4163-992f-9c2c0aa2b043)

![image](https://github.com/user-attachments/assets/c12f8521-1406-49ab-82c2-2dc0ebc9952b)

  </details>

------
<!--## RECOVER-->
![Screenshot 2024-10-28 134912](https://github.com/user-attachments/assets/b595cac7-1881-4388-b3ac-4e5f59a099fc)

<details close> 
<summary> <h3> Nist Cybersecurity Framework 2.0 Pass/Fail logs (Click here)</h3> </summary>

![image](https://github.com/user-attachments/assets/4ff8a12f-562a-4de2-ab15-0f57380f01dd)

  </details>

------

## Recommendations
The following are a set of recommendations based on the NIST assessment.
The recommendations should be priorized in order of importance.
Key Areas of Improvements:

Cyber Security Governance:

• Hire a Cyber security manager or a Chief information security manager.

• Formalize cyber security roles and responsibilities. Ensure that the board of directors are aware of their information security duties

• Draft a comprehensive information security policy. Get the policy endorsed by senior management.

• Invest in hiring cyber security professionals to establish and manage a cyber security practice.

Asset Management:

• Identify and classify all assets based on criticality and sensitivity

• Conduct periodic reviews to ensure the CMDB is accurate and up to date 

Third Party risk management:

• Create a process to identify and manage third party suppliers. The process should start by identifying suppliers, classifying suppliers, and conducting periodic
security assessments on third party suppliers

Cyber Security Risk Management:

• Create a process to assess and manage cyber security risks.

• The process should priorize risks based on criticality and impact to the business.

• The process should be endorsed by the audit and risk commitee and the current risk management team

• Create a cyber security risk register to document all cyber security risks

• Recommend an internal audit program to include cyber security in the scope

Identity and Access Management:

• Implement and roll out two factor authentication across the organization as a priority

• Follow the principle of least privileges and separation of duties across the organization

• Review admin users, eliminate sharing of admin passwords and implement a role based access control

• Conduct regular user access reviews to ensure that access management principles are consistently followed

Security Education and Awareness:

• Employees should undergo security training at least once every 12 months

• Consider running simulated phishing attacks to further improve awareness

Data Security and DLP:

• Undertake a data discovery activity. Classify and label data based on sensitivity and criticality.

• Utilize Microsoft Azure AIP to label data

• Consider implemen1ng a DLP solution. A Microsoft DLP solution might be the best solution as the environment uses Microsoft products.

• Block USB flash drive usage. Only allow it (temporarily) when there is a business justification.

Detection and Response:

• Invest in a SIEM solu1on. This could be using a Managed Security Service Provider (MSSP) or in house. Detecting cyber security incidents is a priority.

• Create an enterprise-wide cyber security incident response plan and at least 5 cyber security incident response plans for the most common attack types.
