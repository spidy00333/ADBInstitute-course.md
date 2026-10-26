# ADBI Cybersecurity Course: Study Notes

Notes from the ADBI E-Learning course *Cybersecurity* (lecturer: Dr. Dalma R. Demeter). Pass mark for the quiz: **8/10**.

| Unit | Topic |
|------|-------|
| 1 | Data Protection (why it matters) |
| 2 | Recognizing Cyberattacks |
| 3 | Data Security Tools (**main focus of these notes**) |

---

# UNIT 3: Data Security Tools

## The 5 steps to protect against cyber threats

**Identification → Protection → Detection → Response → Recovery**

> Memory trick: **I-P-D-R-R**

### 1. Identification
- "You cannot protect what you don't know you have."
- Do a **cybersecurity risk assessment**: find where valuable data is, do threat analysis, manage vulnerabilities.
- Run a **vulnerability scan**, then prioritize mitigation by top risks.
- Identification is **continuous**, because the environment keeps changing.

### 2. Protection
Multi-layered defence: perimeter, cloud, personal devices, anywhere data is accessed.

**Elements of cybersecurity where data may be exposed:**
1. **Application security**: protect software across its whole lifecycle (design → development → deployment → maintenance → upgrade → retirement). Examples: audit external libraries, patch the OS, control who can change applications.
2. **Network security**: who can access the network and what they can access. Examples: Wi-Fi password, guest Wi-Fi, separate file servers (HR / IT / operations), password policies by risk level, **VPN** for remote workers, firewalls and router protection.
3. **Endpoint security**: protects laptops, tablets and smartphones connecting to the network. Treated separately because of its higher vulnerability.
4. **Cloud security**: protects data on the Internet. It is a **shared responsibility** between provider and user.
5. **IoT security**: possibly the **most vulnerable** element (cameras, appliances, voice assistants). Reason: users don't change **default passwords**, and many devices have no security protections.

### The CIA Triad
| Letter | Meaning | Payroll example |
|--------|---------|-----------------|
| **C**onfidentiality | Only authorized people can *see* the data | Only HR, payroll and line managers see payroll records |
| **I**ntegrity | Only authorized people can *modify or delete* it | If you can triple your own salary unnoticed, there is no integrity |
| **A**vailability | People can *access* data when needed | You can read your payslip but not edit your record |

### Preventing breaches

**Smartphones/tablets (least protected):**
- Complex password, updated regularly.
- Tracking, locking and remote wiping (**MDM** = Mobile Device Management software does this).
- Keep OS and apps updated (security patches).
- Don't connect to unknown/unprotected Wi-Fi.

**Business data:** think about where and how it's stored, how it's secured (physically and electronically), who has access, which devices are allowed, and **regular backups stored off-site**.

**DLP (Data Loss Prevention)** monitors, detects and blocks sensitive data **in use, in motion and at rest**. It can disable USB ports, monitor file copying, and block transfers.

**Asset register:** list of all hardware and software (including servers). Record the details of assets at risk and **audit it regularly**.

### Server security
- Implemented in **layers**: base operating system, hosted applications, network security.
- If you don't use a secure data centre: keep servers **locked**, monitor and restrict access, watch security logs, control temperature/fire/ventilation, keep a **stable power supply**.
- **Cloud alternative:** with SaaS/PaaS the provider configures and maintains servers (patching, hardening, logging, auditing).

**Server hardening** = increasing security beyond default configuration:
- Encrypt communications
- Remove unnecessary software
- Update the OS and apply patches regularly
- Use security extensions
- Enforce strong password complexity
- Lock accounts after repeated failed logins
- Use brute-force and intrusion detection systems
- Back up data and systems regularly

### Firewalls, antivirus, MFA
| Tool | Key point |
|------|-----------|
| **Hardware firewall** | Usually in broadband routers; protects the whole local network; works even with minimal configuration |
| **Software firewall** | An application on individual devices, often part of the OS; needs more configuration |
| **Network firewall** | Filters all incoming and outgoing traffic of the business |
| **Antivirus** | Runs in the background to scan, detect, block and eliminate malware |
| **MFA / 2FA** | Several proofs of identity (e.g., password + code sent to another device); protects well against password weaknesses |

Firewall devices can: block malicious email relaying, prevent malware downloads from untrusted sites, block blacklisted sites and unsecured devices.

> **Firewall vs antivirus:** the firewall stops malware from *getting in*; the antivirus recognizes and removes malware that *already reached* the computer or network.

Servers, like desktop PCs, need: **a firewall, regular backups and updates, reliable security software, reliable maintenance and support.**

### 3. Detection
- No protection is foolproof, so threats will slip through. **Monitor 24/7**.
- **Breach/intrusion detection tools** (software or hardware) alert security staff to suspicious user behaviour, network vulnerabilities, or threats in applications. They identify intrusions *after* they happen, contain the breach and limit damage.
- Technology alone is not enough: **skilled security analysts** are needed for decisions requiring human intelligence.

### Glossary of tools and terms (likely quiz material)
| Term | Definition |
|------|------------|
| **WAF** (Web Application Firewall) | Filters and monitors **HTTP traffic** between a web app and the Internet. Can be network-based (hardware), host-based (software) or cloud-based (**most cost-efficient**) |
| **Reverse proxy** | Gateway between users and the origin server; receives requests as if it were the endpoint and forwards them; improves performance and security |
| **Load balancer** | Acts as a reverse proxy; distributes traffic across several servers |
| **DMZ** (Demilitarized Zone) | Perimeter / subnetwork between the public Internet and the private internal network; extra layer of security |
| **CASB** (Cloud Access Security Broker) | Sits **between cloud services and cloud users**; monitors activity and enforces security policies |
| **IAM** (Identity & Access Management) | Right people, right resources, right times, right reasons |
| **CSPM / SSPM** (Cloud / SaaS Security Posture Management) | Continuously benchmarks cloud/SaaS, finds **misconfigurations** and vulnerabilities, prioritizes and fixes them |
| **API** | Interface standardizing how two pieces of software interact; essential data source for security operations |
| **EDR** (Endpoint Detection & Response) | Detects, investigates and mitigates suspicious endpoint activity **without a known signature**; can trigger an adaptive response |
| **XDR** (Extended Detection & Response) | Extends EDR beyond endpoints to a wider set of security telemetry |
| **Open XDR** | **Vendor-neutral** XDR; avoids vendor lock-in; correlates alerts, reduces noise |
| **NOC** (Network Operations Centre) | Keeps IT infrastructure running normally; **not** a security solution against advanced attacks |
| **SOC** (Security Operations Centre) | People + processes + technology for threat detection and incident response; protects against cyberattacks |
| **VA** (Vulnerability Assessment) | Identify, classify and prioritize vulnerabilities, over a determined period of time (internal, external or host-based) |
| **VM** (Vulnerability Management) | Identify, track and prioritize vulnerabilities; optimizes patching, upgrades, configuration fixes |
| **MR** (Managed Risk) | Service that continuously scans networks, endpoints and cloud for risky software, assets, misconfigurations and accounts; goes beyond VM |
| **MDR** (Managed Detection & Response) | Part of **SOC-as-a-service (SOCaaS)**; third-party vendor does monitoring, detection and response |
| **SIEM** (Security Information & Event Management) | Collects and aggregates events/alerts from different security products to spot threats |

- The tools are built on **microservices**, which are many small independent components; the stack is "like a house of cards" and becoming unstable.
- Newer approaches: **zero trust** frameworks and **cybersecurity mesh** (Gartner), but these are beyond the course level.
- Market forecast: over **USD 375 billion by 2029**.

### 4. Response: Cybersecurity Incident Response Plan (IRP)
- "The question is not **whether** you will experience an attack, but **when**."
- An IRP is a document with instructions for responding to a serious incident, breach, leak, ransomware or loss of sensitive information. The quicker the response, the less the damage.
- Three segments: **prepare, deal with the breach, follow up.**

**The 7 stages of incident response:**
1. **Preparation**: be prepared for the worst
2. **Identification**: identify the actual incident
3. **Containment**: stop the problem from spreading
4. **Investigation**: how it happened, how far it spread, what damage
5. **Eradication**: eliminate the breach or infection
6. **Recovery**: restore data from a **clean backup**, mitigate losses
7. **Follow-up**: integrate lessons learned into future plans

**How to build an IRP:**
1. Identify and prioritize assets
2. Identify risks and vulnerabilities
3. Set up a response team (resources + roles and responsibilities)
4. Establish procedures: a checklist (detection and analysis, containment/eradication/recovery, **incident communications**)
5. **Test and regularly update** the plan

**Virus / malware response:**
1. Tell everyone who needs to know (identify the infected file in your notice)
2. Manage or close outgoing email traffic; notify partners/customers if infected mail was already sent
3. **Quarantine** infected machines: disconnect from all networks until cleared
4. Clean-up: scan with antivirus; if needed restore from recent backup, or wipe, reinstall the OS and restore from a clean backup
5. Install the latest updates and patches **before** returning to normal (prevents re-infection)

**Data breach response:**
1. **Contain**: assess nature and scope, consider all affected systems, look for concealed intrusions, reroute or block traffic, isolate/suspend compromised devices
2. **Get specialist help**: technical/security staff, HR (if employees are involved), PR experts (brand damage), data protection experts (personal data), plus a legal adviser and the insurer
3. **Investigate**: find the security gaps, clean systems, get systems running again, address internal/external involvement, record which controls failed
4. **Legal and regulatory notifications**: bank/service providers, regulators (personal data loss; some sectors have specific duties), law enforcement (example in the course: **CamCERT** in Cambodia), and affected individuals (customers, clients, suppliers)
5. **Manage reputation and customer relations**: communicate **quickly, openly and honestly**, don't hide the damage

### 5. Recovery
- More than just backups: **eradicate the threat, then quickly restore** systems and operations.
- A **recovery plan** addresses lack of connectivity, hardware destruction, data corruption and cyberattacks; it minimizes downtime of servers, databases and workstations.
- Not all services need the same speed of recovery, so **prioritize critical ones**.

**Building the recovery plan:**
1. **Map assets** (location, relation to other assets, vendor/version, network parameters)
2. **Criticality:** classify assets as **high / medium / low impact**
3. **Risk assessment** (ask staff who run critical systems)
4. **Define recovery objectives:**
   - **RTO** (Recovery Time Objective) = **maximum time** to restore normal operations after an outage
   - **RPO** (Recovery Point Objective) = **maximum amount of data** the organization can tolerate losing
5. **Recovery setup and tooling:** recovery site (cloud or self-hosted), backups/replicas and where, procedure steps, tools/partners, who does what, budget (cheap = high risk, expensive = low risk)
6. Get feedback and approval, communicate the plan to everyone affected
7. **Test with a realistic drill**, learn from it, adjust
8. **Review at least every 6 months**

---

# UNIT 2: Recognizing Cyberattacks

### Incident vs breach
- **Incident:** security event that compromises **integrity, confidentiality or availability** of an information asset.
- **Data breach:** **confirmed disclosure** (not just potential exposure) of data to an unauthorized party.
- An incident can exist without a breach, and the difference matters for how you respond.

### How cybercriminals make money
Stealing from bank accounts, selling credit card data / PII / personal health information, **ransomware extortion**, trading insider information, **cryptojacking** (using a compromised environment for other attacks / mining).

### Terminology
- **IT** (information technology systems/department) vs **OT** (operational technology: monitors/controls physical devices, e.g., industrial control systems / SCADA; usually run separately from IT)
- **IoT:** everyday devices connected to the internet that collect and exchange data
- **DNS:** translates domain names to IP addresses ("internet phone book"); **IP address:** unique logical address of each device on a network
- **Middleware:** software that integrates applications/databases (3 types: **communication, database, system**). **API:** callable services; middleware is the product that does the integration
- **CASB:** between cloud services and users, enforces policies
- **Bot:** automated software robot (often destructive); not the same as a chatbot. **Botnet:** many infected devices running bots, often rented to other criminals
- **Dark web:** only reachable with special anonymity software; used for black-market sales of stolen data and botnet rentals; payments often in **Bitcoin**
- **Bitcoin:** cryptocurrency created in **2009**; balances on a public ledger; **mining** = solving a computationally hard puzzle to add a block to the blockchain and earn a reward; difficulty rises over time

### 6 action categories (2022 Verizon Data Breach Investigations Report)
| Category | Meaning |
|----------|---------|
| **Hacking** | Intentional unauthorized access/harm by circumventing security |
| **Social** | Deception, manipulation, intimidation; targets the human element |
| **Physical** | Proximity, possession or physical force |
| **Environmental** | Natural events (earthquakes, floods) and hazards in the asset's environment |
| **Misuse** | Using entrusted resources/privileges contrary to their intended purpose |
| **Error** | Anything done incorrectly or left undone that causes a vulnerability or breach |

### Types of attacks
**Social engineering / phishing family**
- **Brute force:** trying all possible passwords; long passwords with letters, numbers and special characters are much harder
- **Phishing:** deceptive email (fake bank) leading to a fake site that steals credentials
- **Smishing** = via SMS; **Vishing** = via phone call
- **Consent phishing:** tricks users into authorizing a malicious app/integration
- **Spear phishing:** targets a specific individual. Sub-types: **cloning** (reuses a previous legitimate email), **whaling** (high-level executive), **HR phishing** (employee data)
- **BEC / EAC** (Business Email Compromise): spoofs a company executive/employee email to get money or data. Look-alike addresses (e.g., "rn" vs "m")

**Malware** (code run on a device that alters its state/function without informed consent)
- **Ransomware:** locks the system or encrypts files, demands ransom (typically **Bitcoin**). **RaaS** = Ransomware-as-a-Service: subscription model for affiliates
- **Scareware** (deception/rogue scanner/fraudware): fake antivirus warnings, pop-ups, fake support numbers
- **Spyware:** secretly collects passwords, ID and payment data; runs in the background
- **Trojan horse:** looks legitimate so users run it; then takes control
- **Adware:** displays ads, may sell browsing behavior
- **Worm:** stand-alone; copies itself across networks **without human interaction** and without attaching to software
- **Virus:** self-replicating; **needs the host to activate it**; sub-category of malware, not a synonym

**Other concepts (alphabetical in the course)**
- **APT** (Advanced Persistent Threat): often nation-state or state-sponsored; political/economic motives
- **Credential stuffing:** logins using previously breached username/password pairs
- **XSS** (Cross-Site Scripting): injects malicious scripts into a trusted website; executes when users visit
- **DoS / DDoS:** flood a network with more traffic than it can handle; DDoS uses many machines, typically a botnet (example: **Estonia**)
- **DNS hijacking** (redirection/poisoning): sends you to the wrong, malicious site
- **Drive-by attack:** malicious code downloaded automatically when visiting a compromised site
- **Exploit:** script/application that takes advantage of a vulnerability
- **Golden ticket attack:** attacker controls the domain's **Key Distribution Service (KDS)** and forges access "tickets"
- **Insider threat:** disgruntled employee leaks data or exposes vulnerabilities
- **Juice jacking:** free charging stations / free Wi-Fi give attackers access to your device
- **MITM** (Man-in-the-Middle): attacker sits unseen between two parties
- **Security misconfiguration:** controls not properly implemented (devices, networks, cloud, firewalls)
- **Supply chain attack:** compromise a third-party vendor to reach the real target (example: **Toyota** closing factories after the supplier Kojima Industries was hit)
- **Web shell:** malicious web-based shell uploaded to a server to run commands

**Physical attacks**
- **Dumpster diving:** collecting sensitive info from bins (solution: shred documents)
- **Shoulder surfing:** looking over someone's shoulder
- **Tailgating:** slipping through a door behind an authorized person

### Prevention checklist
- Security software (antivirus, spam filters, firewall, web filters)
- Keep software updated (security software, OS, browsers, apps)
- **Encryption + VPN** when working remotely
- Regular backups
- Strong complex passwords + **password manager** (not an unprotected document)
- **MFA**

### Recognizing attacks
**Spam:** don't open attachments or links, **don't send read receipts**, filter the sender, delete. Check the junk folder for genuine emails.

**Phishing red flags:** urgency/threats (fine, account closure), suspicious links, spelling/grammar errors (but **AI is improving fakes**, so a perfect message can still be fake).

**What to do with a suspicious message:**
- Go to the site via a **bookmarked** link, not the email link
- Forward (don't reply) to a known sender to confirm, or **call them directly**
- Don't give out personal info unless verified
- **Don't click email links**: type the URL, or **hover** to check the real destination
- **Voice cloning:** AI can clone a voice from ~**3 seconds**; use a **family safe word** and call back on a known number

**Adware signs:** ads in odd places, homepage changes, redirects, slow/crashing browser, new toolbars/extensions, unwanted auto-installs. **Clean:** security software, clear cache/history, or restore a previous OS version (backups!).

**Breach warning signs:** suspicious network activity (file transfers, logins), sudden changes to system passwords/accounts, suspicious/encrypted files, suspicious banking activity, loss of access to accounts, leaked customer data, slow/intermittent connection, genuine antivirus alerts. Breaches can go unnoticed for **months**.

**Website monitoring signs:** odd code, admin login problems, sudden traffic change (e.g., drastic drop), unexplained design/content changes, availability/performance issues.

---

# UNIT 1: Data Protection

- **Cybersecurity** protects data, systems, devices and networks from disclosure, theft or damage, and protects services from disruption. It combines **strategies, people and processes**.
- Analogy used: cybersecurity = **personal hygiene** against bacteria in a constantly changing environment.
- First recorded "hacking": **1834** (signal towers with movable arms, observed by telescope).
- Cybersecurity is **not a fixed science**; it evolves constantly.
- **Examples of attacks:** Estonia (2007-style automated attacks on banks, media, government), Sony Pictures leak, power outages, NASA losing contact with a space station, a virus damaging a country's nuclear infrastructure.
- **2022 examples:** Red Cross (data of 500,000+ people from 60+ National Societies, January), European oil terminals (February), a kettle-thermostat manufacturer, **Toyota** (28 production lines, 14 factories, March), an **Indian airline** ransomware (May), **casino hacked via a fish-tank thermometer** (2018).
- Source for news: **The Hacker News**.
- **Costs:** global cost of cyberattacks **> US$6 trillion in 2021**, forecast **> US$10 trillion by 2025**.
- Cybercrime is one of the **top 3 financial crimes** (with fraud and money laundering).
- **Motive:** financial gain in **over 90%** of cases; espionage/ideology second (< 10%).
- About **half of targets are small and mid-size businesses**.
- **Asia-Pacific (2022):** **59%** of businesses reported being a victim; **32%** multiple times.
- Agriculture and food supply chains can be exposed (Cambridge researchers).
- Most attacks **go undetected**; organizations often learn of breaches **from others** (customers, partners, police) and lack a formal incident response plan.

---

## Quick-recall cheat sheet

- **5 steps:** Identification, Protection, Detection, Response, Recovery
- **CIA:** Confidentiality, Integrity, Availability
- **7 IR stages:** Preparation, Identification, Containment, Investigation, Eradication, Recovery, Follow-up
- **RTO** = max *time* to restore; **RPO** = max *data* you can lose
- **Firewall** keeps malware out; **antivirus** removes what got in
- **NOC** = keeps things running; **SOC** = defends against attacks
- **EDR** = endpoints; **XDR** = wider telemetry; **Open XDR** = vendor-neutral
- **MDR** = outsourced SOC (SOCaaS); **SIEM** = aggregates security events
- **Virus** needs a host to activate; **worm** spreads alone
- **Incident** = compromise event; **breach** = confirmed disclosure
- **Review the recovery plan** at least every **6 months**
- **Most vulnerable element:** IoT (default passwords)
