# Conducting a Security Audit
## **Background**
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location. However, its online presence has grown, attracting customers in the U.S. and abroad. Their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, and completing a risk assessment. The goal of the audit is to provide an overview of the risks the company might experience due to the current state of their security posture. The IT manager wants to use the audit findings as evidence to obtain approval to expand his department. 

## **Scope**
Botium Toys internal IT audit will assess the following:
* Current user permissions set in the following systems: accounting, end point detection, firewalls, intrusion detection system, security information and event management (SIEM) tool. 
* Current implemented controls in the following systems: accounting, end point detection, firewalls, intrusion detection system, Security Information and Event Management (SIEM) tool. 
* Current procedures and protocols set for the following systems: accounting, end point detection, firewall, intrusion detection system, Security Information and Event Management (SIEM) tool. 
* Ensure current user permissions, controls, procedures, and protocols in place align with necessary compliance requirements.
* Ensure current technology is accounted for. Both hardware and system access.

## **Goals**
The goals for Botium Toys’ internal IT audit are:
* To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF) ● Establish a better process for their systems to ensure they are compliant 
* Fortify system controls
* Implement the concept of least permissions when it comes to user credential management
* Establish their policies and procedures, which includes their playbooks
* Ensure they are meeting compliance requirements

## **Assets**
Assets managed by the IT Department include:
* On-premises equipment for in-office business needs
* Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
* Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
* Internet access
* Internal network
* Vendor access management
* Data center hosting services
* Data retention and storage
* Badge readers
* Legacy system maintenance: end-of-life systems that require human monitoring

## **Risk**
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have the proper controls in place and may not be compliant with U.S. and international regulations and standards.

On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to necessary compliance regulations and standards.

## **Impact**
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be lost. The likelihood of a lost asset or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not adhering to required regulations and standards related to keeping customer data private.

## **Controls Assessment**
Controls assessment for administrative controls:
|**Control Name**|**Control type and explanation**|**Needs to be implemented**|**Priority**|
|-----------------|---------------------------------|-----------------------------|--------------|
|Least Privilege|Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs|&#x2611;|High|
|Data Recovery Plans|Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration|&#x2611;|High|
|Password policies|Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques|&#x2611;|High|
|Access control policies|Preventative; increase confidentiality and integrity of data|&#x2611;|High|
|Account management policies|Preventative; reduce attack surface and limit overall impact from disgruntled/former employees|&#x2611;|High|
|Separation of Duties|Preventative; ensure no one has so much access that they can abuse the system for personal gain|&#x2611;|High|  

Controls assessment for technical controls:
|**Control Name**|**Control type and explanation**|**Needs to be implemented**|**Priority**|
|-----------------|---------------------------------|-----------------------------|--------------|
|Firewall|Preventative; firewalls are already in place to filter unwanted/malicious traffic from entering internal network|&#x2612;|Low|
|Intrusion Detection System (IDS)|Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly|&#x2611;|High|
|Encryption|Deterrent; makes confidential information/data more secure (e.g., website payment transactions)|&#x2611;|High|
|Backups|Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan|&#x2611;|High|
|Password management system|Corrective; password recovery, reset, lock out notifications|&#x2611;|Medium|
|Antivirus (AV) software|Corrective; detect and quarantine known threats|&#x2611;|High|
|Manual monitoring, maintenance, and intervention|Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities|&#x2611;|High|

Controls assessment for physical controls:
|**Control Name**|**Control type and explanation**|**Needs to be implemented**|**Priority**|
|-----------------|---------------------------------|-----------------------------|--------------|
|Time-controlled safe|Deterrent; reduce attack surface/impact of physical threats|&#x2611;|Medium|
|Adequate lighting|Deterrent; limit “hiding” places to deter threats|&#x2611;|Low|
|Closed-circuit television (CCTV) surveillance|Preventative/detective; can reduce risk of certain events; can be used after event for investigation|&#x2611;|Medium|
|Locking cabinets (for network gear)|Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear|&#x2611;|Medium|
|Signage indicating alarm service provider|Deterrent; makes the likelihood of a successful attack seem low|&#x2611;|Low|
|Locks|Preventative; physical and digital assets are more secure|&#x2611;|High|
|Fire detection and prevention (fire alarm, sprinkler system, etc.)|Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc.|&#x2611;|High|

## **Compliance Assessment**
&#x2612; **The Federal Energy Regulatory Commission - North American Electric Reliability Corporation (FERC-NERC)** \
The FERC-NERC regulation applies to organizations that work with electricity or that are involved with the U.S. and North American power grid. Organizations have an obligation to prepare for, mitigate, and report any potential security incident that can negatively affect the power grid. Organizations are legally required to adhere to the Critical Infrastructure Protection Reliability Standards (CIP) defined by the FERC.

Not enough information is given to determine whether Botium Toys complies with the FERC-NERC.

&#x2611; **General Data Protection Regulation (GDPR)** \
GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens’ data and their right to privacy in and out of E.U. territory. Additionally, if a breach occurs and a E.U. citizen’s data is compromised, they must be informed within 72 hours of the incident.

As Botium Toys expands to serve customers in Europe, the company must ensure they comply with the GFPR. 

&#x2611; **Payment Card Industry Data Security Standard (PCI DSS)** \
PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment.

Botium Toys is an online retailer which uses credit card payments. Company must ensure they comply with PCI DSS. 

&#x2612; **The Health Insurance Portability and Accountability Act (HIPAA)** \
HIPAA is a federal law established in 1996 to protect U.S. patients’ health information. This law prohibits patient information from being shared without their consent. Organizations have a legal obligation to inform patients of a breach.

Botium Toys does not handle the medical information of it's customers. The HIPAA does not apply in this case.

&#x2611; **System and Organizations Controls (SOC type 1, SOC type 2)** \
The SOC1 and SOC2 are a series of reports that focus on an organization’s user access policies at different organizational levels. They are used to assess an organization’s financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.

Botium Toys must provide appropriate user access to employees and third-part vendors to mitigate risk. 