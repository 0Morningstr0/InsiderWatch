# InsiderWatch
InsiderWatch is an open-source, community-driven Threat Intelligence Platform (TIP) specifically designed to combat Insider Threats and Ghost Workers. It enables security teams to anonymously share and cross-verify indicators of compromised infrastructure without revealing sensitive PII.
InsiderWatch: Community Insider Threat Database

InsiderWatch is an open-source, community-driven Threat Intelligence Platform (TIP) specifically designed to combat Insider Threats and Ghost Workers. It enables security teams to anonymously share and cross-verify indicators of compromised infrastructure without revealing sensitive PII.

🚀 The Core Problem

Insider threat intelligence is traditionally siloed. When one company identifies and blocks a fraudulent contractor or a compromised device, that intelligence rarely leaves their SOC.

InsiderWatch bridges this gap. It allows Organization A to flag a hashed Device ID or suspicious VPN IP, so when Organization B encounters the same actor, they receive an immediate "High Confidence" warning.

✨ Key Features

🔒 Privacy-First Architecture

Client-Side Hashing: Sensitive identifiers (Device IDs, Usernames, Browser Fingerprints) are hashed (SHA-256) inside the browser before transmission.

Zero PII: No personal identifiable information or tenant IDs are stored.

🧠 Context-Rich Intelligence

Unlike simple IP blocklists, InsiderWatch captures the context of a threat:

Identity Context: Job roles (e.g., "DevOps"), Employment Status.

Network Fingerprint: VPN Providers, ISPs, and Geo-location.

Behavioral Flags: Specific TTPs like "Geo-velocity anomaly" or "Token persistence."

🤝 Crowdsourced Enrichment

Confirm & Enrich: Users can verify existing reports.

Smart Scoring: Multiple reports from different sources automatically increase the Confidence Score and update the Last Seen timestamp.
