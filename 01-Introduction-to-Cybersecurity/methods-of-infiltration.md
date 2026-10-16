# Methods of Infiltration

Methods of infiltration are techniques attackers use to gain unauthorized access, disrupt services, intercept communications, or obtain sensitive information.

## 1. Social Engineering

Social engineering involves manipulating people into revealing confidential information or performing actions that compromise security.

**Common Types:**
- **Tailgating:** Following an authorized person into a restricted physical area without permission.
- **Pretexting:** Using a fabricated identity or reason to obtain sensitive information.
- **Quid Pro Quo:** Offering a service or benefit in exchange for information or an action.

**Key Point:** Exploit human trust → Gain information or access.

## 2. Denial-of-Service (DoS)

A DoS attack attempts to make a network, system, or application unavailable to legitimate users.

**Common Methods:**
- **Traffic Overload:** Flooding a target with more traffic than it can handle.
- **Malformed Packets:** Sending invalid or specially crafted packets that disrupt system operations.

**Key Point:** Overwhelm a target → Disrupt service.

## 3. Distributed Denial-of-Service (DDoS)

A DDoS attack uses multiple compromised devices to overwhelm a target with traffic or requests.

### Botnet

A botnet is a group of compromised devices, known as bots or zombies, controlled by an attacker, often through a Command and Control (C2) system.

**Common Uses of Botnets:**
- DDoS attacks
- Spam distribution
- Malware distribution
- Password-guessing attacks

**Detection and Defense:**
- Monitor unusual network traffic.
- Use firewalls and security monitoring tools.
- Investigate suspicious communications with command-and-control infrastructure.
- Apply security updates and isolate infected devices.

**Key Difference:**
- **DoS:** Typically originates from one main source.
- **DDoS:** Uses multiple coordinated sources.

## 4. On-Path Attack

An on-path attack occurs when an attacker intercepts or modifies communication between two parties without their knowledge.

It is also commonly associated with a Man-in-the-Middle (MitM) attack.

**Potential Impacts:**
- Theft of sensitive information
- Interception of unencrypted data
- Impersonation of a communicating party

### Man-in-the-Mobile (MitMo)

MitMo refers to attacks targeting mobile devices to capture or transfer sensitive information. Some malware may intercept verification messages, including SMS-based two-factor authentication codes.

**Key Point:** Intercept communication → Capture or modify information.

## 5. SEO Poisoning

SEO poisoning involves manipulating search engine results to promote malicious websites and attract unsuspecting users.

Attackers may use popular search terms to make harmful websites appear more prominently.

**Key Point:** Manipulated search results → Malicious websites → Potential compromise.

## 6. Wi-Fi Password Attacks

Attackers may attempt to obtain Wi-Fi passwords through several methods:

- **Social Engineering:** Tricking users into revealing a password.
- **Brute-Force Attack:** Trying many possible password combinations.
- **Password Cracking:** Attempting to recover passwords from captured password data.
- **Network Sniffing:** Capturing network traffic, which may expose sensitive information if it is unencrypted.

**Protection:** Use strong, unique Wi-Fi passwords, WPA2-AES or WPA3 security, and updated router firmware.

## 7. Password Attacks

Password attacks are techniques used to guess, obtain, or recover passwords to gain unauthorized access.

### Common Types

**1. Password Spraying**

Trying a small number of common passwords across many accounts.

**Key Point:** Few passwords → Many accounts.

**2. Dictionary Attack**

Using a list of common words and passwords to guess weak or predictable passwords.

**Key Point:** Wordlist → Password guessing.

**3. Brute-Force Attack**

Systematically trying possible password combinations until a match is found or the attempt limit is reached.

**Key Point:** Many possible combinations → Password guessing.

**4. Rainbow Table Attack**

Using precomputed tables of password hashes to help recover passwords from matching hashes, particularly when passwords are not adequately protected with salts and modern password hashing.

**Key Point:** Precomputed hashes → Hash comparison.

**5. Traffic Interception**

Capturing network communications to obtain passwords when they are transmitted without adequate encryption.

**Key Point:** Unencrypted traffic → Potential exposure.

### Password Attack Summary

- **Password Spraying:** Few passwords against many accounts.
- **Dictionary Attack:** Common words and passwords.
- **Brute Force:** Systematic combination guessing.
- **Rainbow Table:** Precomputed password hashes.
- **Traffic Interception:** Capturing exposed credentials in network traffic.

## 8. Advanced Persistent Threat (APT)

An Advanced Persistent Threat (APT) is a prolonged, targeted cyberattack in which an attacker attempts to maintain access to a system or organization while avoiding detection.

**Key Point:** Targeted attack → Persistent access → Long-term objectives.

## Key Takeaways

- **Social Engineering:** Manipulates people.
- **DoS:** Disrupts service availability.
- **DDoS:** Uses multiple sources to disrupt a service.
- **Botnet:** A network of compromised devices.
- **On-Path Attack:** Intercepts or modifies communication.
- **SEO Poisoning:** Promotes malicious websites through manipulated search results.
- **Password Attacks:** Attempt to obtain or guess passwords.
- **APT:** A prolonged, targeted attack.

---

**Purpose:** Educational cybersecurity notes.
