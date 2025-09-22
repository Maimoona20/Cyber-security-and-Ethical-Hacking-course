# 01 Intro to Cybersecurity and Cyber threats

## Definitions
- **CIA tirad**: 
    - it is an info sec benchmark model.
    - used to evaluate the information secuity of an organization. 
    - developed to provide a baseline standard for evaluating and implementing information security.
- **Cybersecurity**: the practice of protecting digital systems, networks, and data from unauthorized access, attacks, or damage through technical, administrative, and physical security measures.
- **Confidentiality**: the characteristic of data or information when it is not made available or disclosed to unauthorized persons or process
- **Integrity**: the property that data has not been altered in an unauthorized manner
- **Availability**: Ensuring timely and reliable access to and use of information by authorized users
- **Privacy**: the right of an individual to control the distribution of information about themselves 
- **Malware**: It is a malicious software used to steal info or damage machine, modify data etc.
    - **Virus**: it is s self replicating program that needs a .exe file to work. it can be downloaded into your system when u click on some link or download a file or program. modifies files and corrupts memory inside the infected system.
    - **Worm** : works on network level, also self replicating. doesnt need a .exe file to work. finds loophole in your network and enters from there. modifies files or network setting insdide the infected system. 
    - **Trojon Horse**: it is a a malicious code packaged as alegitimate software. travels from system to system and can modify or hide files.
    - **Spyware**: used to monitor or "spy on" user. used in phisihing links. 

        - **Phishing**: Phishing is a cyberattack where attackers trick people into giving up sensitive information (like passwords or credit card details) by pretending to be a trusted source. It usually happens through fake emails, messages, or websites designed to look legitimate. 
- **Ransomware**: enters system, encrypts files and asks for ransom in exchange of decryption of the files.
- **DoS/DDoS**: denial of service/ distributed denial of service attacks are those where the attacker or attackers(bots in DDoS) hog resources of a server and legitemate users cant access it.
- **MITM**: Man in the Middle Attack: when an  attacker intercepts the connection between 2 users to either silently monitor or intercept and modify data shared betweeen them. 

## Active and passive attacks: 
**Active Attack** : Directly alters or disrupts systems/data.  
**Passive Attack**: Steals or monitors information without altering it.  

| Attack Type    | Examples                           |
|----------------|------------------------------------|
| Active         | DoS, Man-in-the-Middle, SQL Injection, Malware |
| Passive        | Eavesdropping, Traffic Analysis, Packet Sniffing |

## Maintaining Security of CIA Triad
| CIA TRIAD      | THREATS                | HOW TO  PROTECT |
|----------------|------------------------|-----------------|
| Confidentiality| snoopiing, dumpster diving, wire tapping, social engineering | Use encryption, access control and stegnography|
|Integrity| MITM, impersonation and roleplay attacks| hashing, digital signature, certifications and non repudiation|
|Availability| DDoS, hardware failure, power failures, destruction| redundancy, fault toolerance, patching|

## Extra notes
- hashing is a one way process it can not be dehashed unlice encryption which can be decrypted
- vulnerabilities is what attackers exploit and we take counter measures to secure these vulnerabilities.
- **Governance Elements**: When leaders and management implement the systems and structures that the organization will use to achieve its goals, they are guided by laws and regulations created by governments to enact public policy. Laws and regulations guide the development of standards, which cultivate policies, which result in procedures.
    
    Regulations -> Standards -> Policies -> Procedures

    - **Procedures** are the detailed steps to complete a task that support departmental or organizational policies.
    - **Policies** are put in place by organizational governance, such as executive management, to provide guidance in all activities to ensure that the organization supports industry standards and regulations.
    - **Standards** are often used by governance teams to provide a framework to introduce policies and procedures in support of regulations.
    - Regulations are commonly issued in the form of laws, usually from government (not to be confused with governance) and typically carry financial penalties for noncompliance.
    - **Protocols** 
- ### What is the impact of exploiting vulnerabilities on affected organization
    - **Data Breach / Fraudulent Theft** → Theft of user/customer data, harming system integrity  
    - **Financial Loss & Penalties** → Costs from downtime, legal fines, or sanctions  
    - **Reputation Damage** → Loss of trust from customers, partners, and stakeholders  
    - **Operational Disruption** → Systems compromised, services halted  
    - **Termination / Blacklisting** → Loss of business contracts or being banned from markets  

    
