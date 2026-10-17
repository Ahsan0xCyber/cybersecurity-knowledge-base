# Network Monitoring and NetFlow

## 1. NetFlow

NetFlow is a network protocol technology used to collect information about IP traffic flows.

It helps administrators understand communication patterns between network devices.

NetFlow information can help identify:

- Source and destination IP addresses
- Source and destination ports
- Network protocols
- Traffic volume and timing
- Unusual communication patterns

## 2. NetFlow Collector

A NetFlow collector receives and stores flow records for analysis.

Its functions include:

- Collecting flow data
- Storing traffic records
- Analyzing communication patterns
- Helping establish normal network behavior

## 3. NetFlow Cache

Network devices can maintain flow information for packets that share relevant characteristics.

Common flow attributes include:

- Source IP address
- Destination IP address
- Source port
- Destination port
- Layer 3 protocol
- Input interface
- Traffic classification information, where available

## 4. Baseline Behavior

A **baseline** describes normal network activity over a period of time.

Security teams compare current activity with the baseline to identify anomalies.

Examples of unusual behavior include unexpected traffic spikes, unusual destinations, and abnormal connection patterns.

## 5. Cybersecurity Applications

NetFlow and network monitoring can support:

- Threat detection
- Incident investigation
- Network troubleshooting
- Traffic analysis
- Identification of suspicious communication

**Key Point:** NetFlow generally provides flow metadata, not the complete contents of every packet.
