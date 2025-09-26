# GRC--CAPSTONE-PROJECT-ON-OSCORP-COMPANY
## Assessment And Findings:

## Current Oscorp cyber security team:
 **Cyber security analyst**: generally, responds to cyber incidents as they come and reports
  to Oscorp’s IT manager.
 **Network engineer**: manages the firewalls and reports to the Network Team Leader.                             
 **Cyber Security Consultant**: My new role in Oscorp. I will initially report to the IT
  manager.
  
## Oscorp Current Cyber Security Controls:
**Organisational governance:**  
  - CEO has a clear business strategy for the business. However, roles and responsibilities for cyber security haven’t been defined. They’re assigned to     the IT team. There is no cyber security strategy.
    
## Asset Management:
   - The IT team has a spreadsheet with serial numbers of laptops.
   - The spreadsheet includes the model of each machine and details about the warranty.
   - Oscorp uses Microsoft Office365 and relies exclusively on Software-as-a-Service applications.
   - All data is in Microsoft Azure cloud
   - The IT team uses a Secure Operating Environment (SOE) to image all their laptops with the latest Windows desktop version
    
 ## Business Contnnuity and Disaster Recovery:
   - The IT team conducts regular disaster recovery testing
   - The IT team has clear and documented business continuity plans
   - The IT team takes regular backups. Backups get tested periodically
    
 ## Vulnerability management:
    - Oscorp have purchased Qualys vulnerability scanner.
    - The IT team uses Qualys on an ad-hoc basis.
    - There is no formal vulnerability management program in place.
    - Large number of high and severe vulnerabilities reported by Qualys
    
 ## Risk management:
    - Oscorp has a risk team that performs financial risk actvites.
    - There is no technology or cyber risk process at Oscorp.
    
  ## Third Party Risk Management:
    - Oscorp doesn’t perform any third-party risk management.
    - Contracts are reviewed by procurement and finance, not IT.
    
  ## Identity and Access Management:
    - Oscorp uses MicrosoK Active Directory to manage users and groups
    - There is no privileged access management solution in place
    - Admin account password is shared with a few senior members of the IT team
    - Access to resources is granted upon request
    - The organisation does not use two-factor authentcation for login
    - Complex login passwords are used
    - Employees use a VPN soluDon to login remotely when required
    
 ## Network security:
    - The organisation has Palo Alto Next-Gen firewalls.
    - The firewalls have been configured by the network
    - The firewalls get audited every year by the network team
    - The firewalls get regular updates
    - The IT team have up to date network diagrams. The diagrams include the cloud the environment.
    - The network is segmented using VLANs.
    
  ## Physical Security:
    - Oscorp is a highly secure facility, with state-of-the-art CCTV cameras everywhere
    - Oscorp takes physical security very seriously
    - They do extensive vetting for all their employees
    - The have a 24/7 monitoring for their research labs and physical facilities
    
  ## Data Security:
    - Oscorp doesn’t have a DLP solution
    - All data resides in Microsoft Azure cloud and Microsoft Office 365
    - Key critical application is a SaaS service from Horizon Labs.
    
  ## Policy:
    - There is one generic IT policy in place
    - No formal information security policy
    - There is no data governance policies or information classification
  ## Cyber Security detection and response:
    - There is no detection or response capability
    - The IT team responds to alerts from the anD-virus (Microsoft Defender)
    - No SIEM in place
  ## Security Education and Awareness:
    - All employees are required to do an induction web training module. The
    module includes basic instructions about cyber security.

# CAPSTONE-PROJECT-SOLUTION: RECOMMENDATIONS:
The following are a set of recommendation based on the NIST assessment that you
conducted.
The recommendations should be prioritised in order of importance.
## Key Areas of Improvements:
    - Cyber Security Governance:
    - Hire a Cyber security manager or a Chief information security manager.
    - Formalise cyber security roles and responsibilities. Ensure that the board of the
  directors are awareness of their information security du1es
    - Draft a comprehensive informa1on security policy. Endorse the policy by senior
  management.
    - Invest in hiring cyber security professionals to establish and manage a cyber
  security practice.
## Asset Management:
    - Identify and classify all assets based on criticality and sensitivity
    - Conduct periodic reviews to ensure the CMDB is accurate and up to date
## Third Party risk management:
    - Create a process to identify and manage third party suppliers. The process should
  start by identifying suppliers, classifying suppliers, and conducting periodic
  security assessments on third party suppliers
## Cyber Security Risk Management:
    - Create a process to assess and manage cyber security risks.
    - The process should prioritise risks based on criticality and impact to the business.
    - The process should be endorsed by the audit and risk committee and the current
  risk management team
    -  Create a cyber security risk register to document all cyber security risks
    - Recommend an internal audit program to include cyber security in the scope
## Identity and Access Management:
    - Implement and roll-out two factor authentcation across the organisation as a
  priority
    -  Follow the principle of least privileges and separa1on of du1es across the
  organisation
    - Review admin users, eliminate sharing of admin passwords and implement a role
  based access control
    - Conduct regular user access reviews to ensure that access management
  principles are consistently followed
## Security Education and Awareness:
    - Employees should undergo security training at least once every 12 months
    - Consider running simulated phishing aNacks to further improve awareness
## Data Security and DLP:
    - Undertake a data discovery activity. Classify and label data based on sensitivity
  and cri1cality.
    - Utilise Microsoft Azure AIP to label data
    - Consider implementing a DLP soluton. A Microsoft DLP solution might be the
  best solution as the environment uses Microsoft products.
    - Block USB flash drive usage. Only allow it (temporarily) when there is a business
  justification.
## Detection and Response:
    - Invest in a SIEM solution. This could be using a Managed Security Service
  Provider (MSSP) or in house. Detecting cyber security incidents is a priority.
    - Create an enterprise-wide cyber security incident response plan and at least 5x
  cyber security incident response plans for the most common attack types.
