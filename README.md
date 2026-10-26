# ADBInstitute-course
# ADBI Cybersecurity Course: My Notes

I took the free **Cybersecurity** course from the ADBI E-Learning platform (Asian Development Bank Institute, taught by Dr. Dalma Demeter). It has three short units, and I wrote these notes to help me remember the essentials and to have them in one place.

---

## Unit 1: Why data protection matters

Cybersecurity is about protecting data, systems, devices and networks from theft, damage and disruption. It's easy to ignore until something goes wrong, but everyone is exposed, not only big companies.

What stuck with me:
- Cybercrime costs the world more than **US$6 trillion a year** (2021), and the figure keeps growing.
- Over **90%** of attacks are about money.
- About half of the victims are **small and medium businesses**.
- Even a harmless gadget can be a way in: a casino was hacked through a **fish-tank thermometer**.
- Most attacks go unnoticed, and many companies only find out from a customer or the police.

---

## Unit 2: Recognizing cyberattacks

**Incident vs breach.** An *incident* is any event that compromises the confidentiality, integrity or availability of data. A *breach* is when data is **confirmed** to have been disclosed to someone unauthorized. Every breach is an incident, but not every incident is a breach.

**The attacks I should be able to name:**
- **Brute force:** trying every possible password until one works. Long, mixed passwords make it much harder.
- **Phishing:** fake emails or sites that steal your credentials. *Smishing* is by SMS, *vishing* is by phone, and *spear phishing* targets one person (whaling targets executives).
- **Ransomware:** locks your files until you pay.
- **Spyware, adware, trojans:** spy on you, spam you with ads, or pretend to be legitimate software.
- **Virus vs worm:** a virus needs you to activate it, a worm spreads by itself.
- **DDoS:** floods a network with traffic until it crashes.
- **Man-in-the-middle, supply chain attacks, juice jacking** (free charging stations and Wi-Fi), and physical tricks like **tailgating** and **shoulder surfing**.

**How to spot trouble:**
- Be suspicious of urgency ("your account will be closed!"). Don't click links in emails; type the address yourself or use a bookmark.
- AI now writes perfect fake messages, so a message with no typos can still be fake. AI can even copy a voice from a few seconds of audio, so a family **safe word** is a good idea.
- Signs of a breach: strange files, a slow computer, lost access to accounts, odd bank activity, or a real antivirus warning.

---

## Unit 3: Data security tools

The course organizes protection into five steps: **Identification, Protection, Detection, Response, Recovery.**

**1. Identification.** You can't protect what you don't know you have. Find where your valuable data is and scan for vulnerabilities, and keep doing it, because things change.

**2. Protection.** Several layers: application security, network security, endpoint security, cloud security, and IoT (often the weakest link because people never change default passwords). Everything rests on the **CIA triad**:
- **Confidentiality:** only the right people see the data.
- **Integrity:** only the right people can change it.
- **Availability:** you can reach it when you need it.

Useful tools: firewalls (they keep malware out), antivirus (it removes what got in), **MFA**, VPNs, backups kept off-site, data loss prevention, and **server hardening** (remove what you don't need, patch, lock accounts after failed logins).

**3. Detection.** No protection is perfect, so monitor all the time. Intrusion detection tools raise alerts, but skilled analysts still make the decisions. Terms worth knowing:
- **WAF:** filters web traffic.
- **CASB:** sits between cloud services and users.
- **EDR / XDR:** detect suspicious activity on endpoints, and across more systems.
- **SIEM:** collects security alerts in one place.
- **SOC:** the team defending against attacks. The **NOC** only keeps the network running.
- **MDR:** a SOC provided as a service by an outside vendor.

**4. Response.** It's not *if* an attack happens, but *when*, so have a plan ready. The seven stages: **Preparation, Identification, Containment, Investigation, Eradication, Recovery, Follow-up.**

For a data breach, the order matters: **contain first**, then get specialist help, investigate, notify the right people (regulators, law enforcement, affected customers), and communicate honestly.

**5. Recovery.** Remove the threat, then restore from a clean backup. Two numbers define the plan:
- **RTO:** the longest you can afford to be down.
- **RPO:** the most data you can afford to lose.

Test the plan with a drill and review it **at least every six months**.

---

## Quick reminders

- Firewall keeps threats out, antivirus cleans up what got in.
- Incident is not the same as breach.
- Contain first, notify after.
- RTO is about time, RPO is about data.
- Don't click, verify.
