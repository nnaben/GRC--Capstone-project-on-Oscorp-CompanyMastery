# GRC--CAPSTONE-PROJECT-ON-OSCORP-COMPANY
# Findings After Assessment Are As Follows:

# Current Oscorp cyber security team:
  Cyber security analyst: generalist, responds to cyber incidents as they come. Reports
  to Oscorp’s IT manager.
  Network engineer: manages the firewalls. Reports to the Network Team Leader.
  Cyber Security Consultant: your new role it Oscorp. You will initially report to the IT
  manager.
  
# Oscorp Current Cyber Security Controls:
  Organisational governance:
  CEO has a clear business strategy for the business. However, roles and
    responsibilities for cyber security haven’t been defined. They’re assigned to
    the IT team. There is no cyber security strategy.
    
 Asset Management:
    The IT team has a spreadsheet with serial numbers of laptops.
    The spreadsheet includes the model of each machine and details about the
    warranty.
    Oscorp uses MicrosoK Office365 and relies exclusively on Software-as-a-
    Service applicaDons.
    All data is in Microsoft Azure cloud
    The IT team uses a Secure Operating Environment (SOE) to image all their
    laptops with the latest Windows desktop version
    
  • Business Contnnuity and Disaster Recovery:
    o The IT team conducts regular disaster recovery testing
    o The IT team has clear and documented business continuity plans
    o The IT team takes regular backups. Backups get tested periodically
    
  • Vulnerability management:
    o Oscorp have purchased Qualys vulnerability scanner.
    o The IT team uses Qualys on an ad-hoc basis.
    o There is no formal vulnerability management program in place.
    o Large number of high and severe vulnerabilities reported by Qualys
    
  • Risk management:
    o Oscorp has a risk team that performs financial risk acDviDes.
    o There is no technology or cyber risk process at Oscorp.
    
  • Third Party Risk Management:
    o Oscorp doesn’t perform any third-party risk management.
    o Contracts are reviewed by procurement and finance, not IT.
    
  • IdenDty and Access Management:
    o Oscorp uses MicrosoK Active Directory to manage users and groups
    o There is no privileged access management soluDon in place
    o Admin account password is shared with a few senior members of the IT team
    o Access to resources is granted upon request
    o The organisaDon does not use two-factor authenDcaDon for login
    o Complex login passwords are used
    o Employees use a VPN soluDon to login remotely when required
    
  • Network security:
    o The organisation has Palo Alto Next Gen firewalls.
    o The firewalls have been configured by the network
    o The firewalls get audited every year by the network team
    o The firewalls get regular updates
    o The IT team have up to date network diagrams. The diagrams include the
    cloud the environment.
    o The network is segmented using VLANs.
    
  • Physical Security:
    o Oscorp is a highly secure facility, with state-of-the-art CCTV cameras
    everywhere
    o Oscorp takes physical very seriously
    o They do extensive vetting for all their employees
    o The have a 24/7 monitoring for their research labs and physical facilities
    
  • Data Security:
    o Oscorp doesn’t have a DLP soluDon
    o All data resides in Microsoft Azure cloud and Microsoft Office 365
    o Key critical application is a SaaS service from Horizon Labs.
    
  • Policy:
    o There is one generic IT policy in place
    o No formal informaDon security policy
    o There is no data governance policies or informaDon classificaDon
  • Cyber Security detection and response:
    o There is no detecDon or response capability
    o The IT team responds to alerts from the anD-virus (Microsoft Defender)
    o No SIEM in place
  • Security Education and Awareness:
    o All employees are required to do an inducDon web training module. The
    module includes basic instrucDons about cyber security.

# Capstone-Project-Solution: RECOMMENDATIONS:
The following are a set of recommendation based on the NIST assessment that you
conducted.
The recommendations should be prioritised in order of importance.
# Key Areas of Improvements:
  • Cyber Security Governance:
  • Hire a Cyber security manager or a Chief informa1on security manager.
  • Formalise cyber security roles and responsibili1es. Ensure that the board of the
  directors are awareness of their information security du1es
  • DraI a comprehensive informa1on security policy. Endorse the policy by senior
  management.
  • Invest in hiring cyber security professionals to establish and manage a cyber
  security practice.
Asset Management:
  • Identify and classify all assets based on criticality and sensitivity
  • Conduct periodic reviews to ensure the CMDB is accurate and up to date
Third Part risk management:
  • Create a process to iden1ty and manage third party suppliers. The process should
  start by identifying suppliers, classifying suppliers, and conducting periodic
  security assessments on third party suppliers
Cyber Security Risk Management:
  • Create a process to assess and manage cyber security risks.
  • The process should prioritise risks based on criticality and impact to the business.
  • The process should be endorsed by the audit and risk commiNee and the current
  risk management team
  • Create a cyber security risk register to document all cyber security risks
  • Recommend an internal audit program to include cyber security in the scope
Iden1ty and Access Management:
  • Implement and roll-out two factor authentcation across the organisa1on as a
  priority
  • Follow the principle of least privileges and separa1on of du1es across the
  organisa1on
  • Review admin users, eliminate sharing of admin passwords and implement a role
  based access control
  • Conduct regular user access reviews to ensure that access management
  principles are consistently followed
Security Educa1on and Awareness:
  • Employees should undergo security training at least once every 12 months
  • Consider running simulated phishing aNacks to further improve awareness
Data Security and DLP:
  • Undertake a data discovery ac1vity. Classify and label data based on sensi1vity
  and cri1cality.
  • Utilise Microsoft Azure AIP to label data
  • Consider implementing a DLP soluton. A Microsoft DLP solution might be the
  best solution as the environment uses Microsoft products.
  • Block USB flash drive usage. Only allow it (temporarily) when there is a business
  justifica1on.
Detection and Response:
  • Invest in a SIEM solution. This could be using a Managed Security Service
  Provider (MSSP) or in house. Detecting cyber security incidents is a priority.
  • Create an enterprise-wide cyber security incident response plan and at least 5x
  cyber security incident response plans for the most common attack types.
