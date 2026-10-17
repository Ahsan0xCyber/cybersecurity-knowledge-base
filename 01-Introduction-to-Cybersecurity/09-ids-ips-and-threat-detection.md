# IDS, IPS, and Threat Detection

## 1. IDS (Intrusion Detection System)

An IDS monitors network or system activity to identify suspicious behavior.

- Detects malicious activity using rules, signatures, or other detection methods.
- Logs detections and generates alerts.
- Typically does not directly block the detected traffic.

A network IDS may receive a copy of network traffic through a monitoring port.

## 2. IPS (Intrusion Prevention System)

An IPS inspects traffic and can block or deny traffic identified as malicious.

It is commonly deployed inline, allowing traffic to pass through the system.

### IDS vs. IPS

- **IDS:** Detects + Logs + Alerts.
- **IPS:** Detects + Blocks.

## 3. Snort

Snort is a well-known open-source network intrusion detection and prevention system that can analyze traffic using rules.

## 4. Real-Time Threat Detection

Real-time monitoring helps organizations identify suspicious activity and respond quickly.

Common security technologies include:

- Firewalls
- IDS and IPS
- Endpoint antimalware
- Security monitoring and threat intelligence systems
- Behavioral analysis

## 5. Behavior-Based Detection

Behavior-based detection identifies deviations from normal system or network activity.

An unusual pattern may indicate an attack, compromised account, or misconfigured system.

## 6. Honeypots

A **honeypot** is a decoy system or service designed to attract and observe suspicious activity.

It can help security teams:

- Record attacker interactions.
- Analyze techniques and behavior.
- Improve detection and defense.

A honeypot must be isolated and monitored carefully.

## 7. DDoS Detection

A **Distributed Denial-of-Service (DDoS)** attack attempts to disrupt a service by overwhelming it with traffic or requests from multiple sources.

Detection can be difficult because:

- Traffic may originate from many compromised devices.
- Malicious requests may resemble legitimate traffic.
- Attacks can affect service availability.

**Key Point:** Monitoring, traffic analysis, filtering, and incident response help mitigate DDoS attacks.
