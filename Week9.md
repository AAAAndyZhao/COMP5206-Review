# Week 9 #

## 1. Information Security ##

- Information Security
  - All of the processes and policies designed to protect an organization’s information and information systems from unauthorized access, use, disclosure, modification, or destruction.
- Threat
  - Any danger which a system may be exposed.
- Vulnerability
  - The possibility that the system will be harmed by a threat.
- Factors contributing to the increasing vulnerability of   organizational resources:
  - Today’s interconnected, interdependent, wirelessly networked businessenvironment
  - Smaller, faster, cheaper computers and storage devices
  - Decreasing skills necessary to be a computer hacker
  - Internationally organized crime
  - Lack of management support

### 1.1. Information Security Threats ###

- Malware from Internet
- Denial of Service from Internet
- Unauthorized Users from Internet
- Natural Disasters (floods, storms)
- Man-Made Disasters (Fire, Power Outage, other accidents)
- Application Progammer
- System Administrator
- Operators
- Users
- System Software
- Other Insiders
- Hardware Threats
- Terminal
- PCS
- Databases

### 1.2. Unintentional Threats ###

Acts performed without malicious intent that nevertheless represent a serious threat to IS security.

- Human Errors
- Social Engineering: An attack in which the criminal uses social skills to manipulate legitimate employees into providing confidential company information such as passwords.
- Tailgating:A wrongdoer enters restricted areas by following closely behind a legitimate employee.
- Shoulder Surfing: A wrongdoer observes an employee’s computer screen over the employee’s shoulder.

### 1.3. Deliberate Threats ###

- Software attacks
- Alien software
- Identify theft
- Theft of equipment and information
- Spying or trespass
  - Occurs when an unauthorized individual attempts to gain illegal access to organizational information
- Information extortion
  - Occurs when an attacker either threatens to steal, or actually steals, information from a company
- Sabotage and vandalism
  - Deliberate acts that involve defacing an organization’s Web site, possibly causing the organization to lose its image and experience a loss of confidence by its customers
- Cyberterrorism and cyberwarfare
  - Malicious acts in which attackers use a target’s computer systems, particularly via the Internet, to cause physical, real-world harm or severe disruption, usually to carry out a political agenda

### 1.4. Software Attacks ###

Occur when malicious software (malware) penetrates an organization’s computer system.

Remote attacks requiring user action

- Virus
  - Segment of computer code that performs malicious actions by attaching to another computer program.
- Worm
  - Segment of computer code that performs malicious actions and will replicate, or spread, by itself (without requiring another computer program).
- Phishing
  - Attack that uses deception to acquire sensitive personal information by masquerading as official-looking emails or instant messages.
- Spear phishing
  - Target a specific person or organization by personalizing the message.
  - The perpetrators find out as much information about an individual as possible to improve their chances that phishing techniques will be able to obtain sensitive, personal information.
- Ransomeware
  - locks up the files on your computer and encrypts them in a way that you cannot access them anymore.
  - **How does it spread?**
    - Ransomware is a program that gets into your computer, either by clicking on the wrong thing or downloading the wrong thing, and then it holds something you need to exchange or pay.
    - it can also spread through phishing emails or via a website containing a malicious program.
    - WannaCry is not just a ransomware program, it's also a worm, This means that it gets into your computer and looks for other computers to try and spread itself as far and wide as possible.
    - (Signs of a Scam) This means that it gets into your computer and looks for other computers to try and spread itself as far and wide as possible, including: the email, text or phone call is unexpected; there's a deadline or sense of urgency; there's a promise of financial benefit or a threat of fines, debts or jail.
- Trojan horse
  - A software program containing a hidden function that presents a security risk
- Back door
  - Typically a password, known only to the attacker, that allows him or her to access computer system at will, without having to go through any security procedures.
- Logical Bomb  
  - Segment of computer code that is embedded within an organization’s existing computer programs and is designed to activate and perform a destructive action at a certain time or date.
- Denial-of-service attack (DoS)
  - A cyber attack in which an attacker sends a flood of data packets to the target computer, which the aim of overloading its resources.
  - Attacker sends so many information requests to a target computer system that the target cannot handle them successfully and typically crashes.
- Distributed denial-of-service attack (DDoS)
  - A denial-of-service attack that sends a flood of data packets from many compromised computers simultaneously
  - An attacker first takes over many computers (bots or zombies), typically by using malicious software, to form a botnet. The attacker uses the botnet to deliver a coordinated stream of information requests to a target computer, causing it to crash

Secret software that is installed on your computer through two-faced methods

- Typically not as malicious as viruses, worms, or Trojan horses, but does use up valuable system resources
- May report on your Web surfing habits and other personal behavior
- Adware
  - Software that causes pop-up advertisements to appear on your screen
- Spyware
  - Software that collects personal information about users without their consent
  - Keyloggers (Keystroke loggers)
    - Spyware that captures keystrokes
  - Screen scrapers (screen grabbers)
    - Software that records a continuous “move” of a screen’s contents rather than simply recording keystrokes.
- Spamware
  - Pestware that uses your computer as a launch pad for spammers.
  - Spam: Unsolicited electronic messages, usually for the purpose of advertising products and/or services
- Cookies
  - Small amounts of information that Web sites store on your computer, temporarily or more or less permanently

### 1.5. Identify Theft ###

The deliberate assumption of another person’s identity and uses his or her personal information for some fraud

- Obtaining personal information by
  - Stealing mail or dumpster diving
    - The practice of rummaging through commercial or residential trash to find information that has been discarded
  - Stealing personal information from computer databases
  - Insightful organizations that store large amounts of personal information
  - Impersonating a trusted organization in an electronic communication (phishing)

### 1.6. Organisational Information Leakage ###

Information leakage as “a breach of the confidentiality of information.”
Organizations face more challenges in protecting their information due to employees’ careless behaviour while using Online Social Network (OSN) that leads to unintended leakage of confidential and sensitive information.
The flow of information published on OSN sites is difficult to control since it can be stored in various formats, copied and distributed to other people.

### 1.7 IS Security Risk Management ###

1. IS security risk
   - The probability that a security threat will impact an information resource
2. Goal of risk management
   - The probability that a security threat will impact an information resource
   - To reduce risk to acceptable levels
3. Risk management process
   - Risk analysis
   - Risk mitigation
   - Controls evaluation

#### 1.7.1 Risk Analysis ####

Three Steps:

1. Assessing the value of each asset being protected
2. Estimating the probability that each asset will be compromised
3. Comparing the probable costs of the asset’s being compromised with the costs of protecting that asset

#### 1.7.2 Risk Mitigation ####

Two Functions:

1. Implementing controls to prevent identified threats from occuring
2. Developing a means of recovery if the threat becomes a reality

Three Strategies:

1. Risk Acceptance
   - Accept the potential risk, continue operating with no controls, and absorb any damages that occur
2. Risk Limitation
   - Limits the risk by implementing controls that minimize the impact of the threats
3. Risk Transference
   - Transfer the risk by using other means to compensate for the loss, such as by purchasing insurance

#### 1.7.3 Controls Evaluation ####

**Description:** Examines the costs of implementing adequate control measures against the value of those control measures

**Defense-in-depth:**

1. Employee multiple layers of controls to avoid a single point-of-failure
2. Preventive controls
   - To limit actions to those in accord with the organization’s security policy and to not allow undesired actions
3. Detective controls
4. Corrective controls
   - To restore a system to its normal operations after a security incident has occurred

**Time-based Model of Security:**

Evaluate the effectiveness of an organization's security

- P(t): Probability of a successful attack
- D(t): Value of the asset being protected
- C(t): Cost of protection
- if P(t) > D(t) + C(t), then the organisation's security procedures are effective

Example:
XYZ Company evaluates its security procedures with the following outcomes:

- Estimated time for intruder to successfully penetrate system = 22 minutes
- Estimated time to detect an intrusion attempt and notify appropriate security staff = 15 minutes
- Estimated time to analyze detected intrusion attempts and implement corrective actions = 6 minutes
- **Are the security procedures of XYZ Company effective?**
**Answer**: **No**, because P(t) > D(t) + C(t), where P(t) = 22 minutes, D(t) = 15 minutes, and C(t) = 6 minutes (22 > 15 + 6).

### 1.8 Infromation Security Controls ###

- Physical controls
  - Prevent unauthorized individuals from gaining access to a company’s facilities
  - Examples: Fences, locks, security guards, alarm systems, etc.
- Access controls
  - Restrict unauthorized individuals from using information resources and include:
    - Authentication
    - Authorization
    - Access levels
    - Access control lists
    - Passwords
    - Tokens
    - Smart cards
    - Biometric authentication
- Communication controls
  - Secure the movement of data across networks
  - Examples: Firewalls, anti-malware systems, whitelisting, blacklisting, encryption, etc.

#### 1.8.1 Access Controls ####

- **Authorization:**
  - A process that determines which actions, rights, or privileges the user has, based on his or her identity.
- **Authentication**
  - A process that determines the identity of the person requiring access.
  - Factors:
    - Something the user knows
    - Something the user has
    - Something that is part of the user
    - Something the user does
  - Two-factor authentication
    - A process that requires two means of identification, one of which is typically a physical token, such as a card, and the other of which is typically something memorized, such as a password.
  - CAPTCHA
    - Completely Automated Public Turing test to tell Computers and Humans Apart.
    - Test to **determine whether the user is human.**

#### 1.8.2 Communication Controls ####

Antivirus software

- Software packages that attempt to identify and eliminate viruses and worms, and other malicious software

Firewalls

- A system (hardware, software, or both) that prevents a specific type of information from moving between untrusted networks (e.g., Internet) and private networks (e.g., Intranet)

Blacklisting & Whitelisting

- A process in which a company identifies certain IP addresses, Web sites, or keywords that are not allowed to appear on employees’ computers (blacklisting) or identifies a list of approved Web sites that can appear on employees’ computers (whitelisting)

Employee monitoring systems

- Systems that monitor employees’ computers, e-mail activities, and Internet surfing activities

Encryption

- Symmetric and asymmetric encryption
- Digital signatures and certificates, and Certificate Authorities (CAs)
- Secure Sockets Layer (SSL) and Transport Layer Security (TLS)
- Virtual Private Networks (VPNs)

#### 1.8.3 Encryption ###

The process of converting an original message into a form that cannot be read by anyone except the intended receiver

- Symmetric encryption
  - The same key is used to encode and decode
  - Examples: DES, AES, 3DES
- Asymmetric encryption
  - Two keys are used: a public key and a private key
  - Examples: RSA, ECC
  - Private Key is used to both encrypt and decrypt the data and is shared between the sender and receiver of encrypted data.
  - Public Key is used to encrypt the data and is available to anyone who wants to send the sender a message.
- Digital signatures
  - A means of electronically signing a document with data that cannot be forged
  - A digital signature is a mathematical scheme for demonstrating the authenticity of digital messages or documents.
  - A valid digital signature gives a recipient reason to believe that the message was created by a known sender (authentication), that the sender cannot deny having sent the message (non-repudiation), and that the message was not altered in transit (integrity).
- Digital certificates
  - A data file that identifies individuals or organizations online and is comparable to a digital signature
  - A digital certificate is an electronic "credit card" that establishes your credentials when doing business or other transactions on the Web.
  - CA (Certificate Authority)
    - A trusted third-party organization or company that issues digital certificates used to create digital signatures and public-private key pairs (e.g., VeriSign, Entrust, Thawte, etc.) and is comparable to a notary public in the physical world (e.g., a notary public verifies the identity of a person signing a document and then stamps the document with his or her seal of approval).
    - A certificate authority (CA) is a trusted entity that issues electronic documents that verify a digital entity’s identity on the Internet.
    - The electronic documents, which are called digital certificates, are an essential part of secure communication and play an important part in the public key infrastructure (PKI).


### 1.9 Business Continuity Planning (BCP)/ IS Auditing ###

Business continuity planning (Disaster recovery planning)

- Identifies an organization's exposure to internal and external threats and provides guidance for effective prevention and recovery for the organization
- Business continuity strategies
  - Hot site
    - A fully configured computer facility, with all the information resources and services, communications links, and physical plant operations, that duplicates a company’s computing resources and provides near-real-time recovery of IT operations
  - Warm site
    - A site that provides many of the same services and options of the hot site, but does not include the company’s applications
  - Cold site
    - A backup location that provide only rudimentary services and facilities (e.g., building with heating, air conditioning, and humidity control)
- IS auditing
  - An examination of information systems by internal or external auditors.

### 1.10 Additional Resource ###

Australia's cyber security watch room is monitoring threats 24/7. What's it like inside? | ABC News
<https://www.youtube.com/watch?v=Ngv09DumPDM>

Australian Cyber Security Centre
<https://www.youtube.com/watch?v=jvoajglQi68>

Australian Government Information Security Manual
<https://www.cyber.gov.au/acsc/view-all-content/ism>

Keypoints:

1. The cyber security watch room is constantly monitoring for threats targeting Australia. The analysts there collect intelligence about everything from scam emails to malicious software.

2. The COVID-19 pandemic has increased their workload, with cyber criminals launching phishing campaigns related to stimulus measures.

3. A particular focus is on remote access trojans, which are tools that criminals use to gain access to systems.

4. The strategies used by cyber criminals are sophisticated and constantly changing, so the analysts need to stay one step ahead.

5. The watch room also has a table used to simulate how authorities might fight an urban cyber attack, showing how power grids and water services could be sabotaged.

6. The Australian government plans to enhance the country's defensive capabilities online, including a $470 million investment for 500 new jobs at the Australian Signals Directorate, where the centre is located.

7. The new employees could be part of teams doing data analytics, dissecting ransomware, or assisting industries like hospitals or banks to restore their tech systems.

8. However, these new employees would need to pass the cyber security agency's rigorous background checks.