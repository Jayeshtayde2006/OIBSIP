Network Security Threats Research Report

Internship Task 4 – Research Report on Common Network Security Threats
Prepared by: Jayesh Tayade
Role: Cyber Security Intern
Organisation: OIBSIP
Location: India

1. Introduction

During my internship, I was introduced to the fundamentals of network security and the various threats that affect organisations worldwide. As someone exploring this field for the first time in a practical environment, I realised how critical network security has become, especially in India where digital transformation, UPI payments, online banking, e-governance services, and cloud adoption are growing rapidly.

This report discusses some of the most common network security threats:

Denial of Service (DoS) and Distributed Denial of Service (DDoS) Attacks

Man-in-the-Middle (MITM) Attacks

Spoofing Attacks

For each threat, I have explained how it works, its impact, real-world examples (including India-specific context), and preventive measures.

2. Understanding Network Security

Network security refers to the protection of computer networks from unauthorized access, misuse, modification, or denial of service. It includes:

Firewalls

Intrusion Detection Systems (IDS)

Intrusion Prevention Systems (IPS)

Encryption

Authentication mechanisms

Network monitoring tools

In India, with initiatives like Digital India and increasing internet penetration even in rural areas, protecting networks has become a national priority.

3. Denial of Service (DoS) and Distributed Denial of Service (DDoS) Attacks
3.1 What is a DoS Attack?

A Denial of Service (DoS) attack is an attempt to make a system, server, or network unavailable to legitimate users by overwhelming it with excessive traffic or malicious requests.

A Distributed Denial of Service (DDoS) attack is a more advanced form where the attack traffic comes from multiple compromised systems (often part of a botnet).

3.2 How It Works

In a DDoS attack:

The attacker infects multiple devices with malware.

These infected devices form a botnet.

The botnet sends a massive number of requests to a target server.

The server becomes overloaded and cannot handle legitimate traffic.

Types of DDoS attacks include:

Volumetric attacks (flooding bandwidth)

Protocol attacks (exploiting weaknesses in network protocols)

Application layer attacks (targeting web applications)

3.3 Impact

Website downtime

Financial losses

Damage to brand reputation

Service disruption in banking, e-commerce, and government services

In India, where many businesses rely heavily on online platforms (Flipkart, Paytm, banking portals), such attacks can cause significant disruption.

3.4 Real-World Example

In 2016, the Dyn DNS attack disrupted major websites globally using a massive DDoS attack powered by IoT devices. Although not India-specific, it affected Indian users accessing global services.

India has also seen DDoS attacks targeting:

Banking institutions

Government portals

Stock exchange-related systems

CERT-In frequently reports such incidents.

3.5 Mitigation and Prevention

Use of Web Application Firewalls (WAF)

DDoS protection services (e.g., cloud-based mitigation services)

Load balancing

Rate limiting

Network traffic monitoring

Redundant server infrastructure

Organisations in India should follow CERT-In guidelines and conduct periodic vulnerability assessments.

4. Man-in-the-Middle (MITM) Attacks
4.1 What is a MITM Attack?

A Man-in-the-Middle attack occurs when an attacker secretly intercepts and possibly alters communication between two parties without their knowledge.

For example, when a user communicates with a bank server, the attacker positions themselves between the user and the server.

4.2 How It Works

Common MITM techniques include:

ARP Spoofing

DNS Spoofing

Rogue Wi-Fi hotspots

SSL Stripping

Example scenario:

User connects to public Wi-Fi in a railway station.

Attacker creates a fake Wi-Fi network with a similar name.

User connects to the fake network.

Attacker intercepts login credentials and sensitive information.

4.3 Impact

Theft of banking credentials

UPI fraud

Identity theft

Data manipulation

In India, where digital payments (UPI, net banking, wallets) are widely used, MITM attacks can lead to direct financial loss.

4.4 Real-World Example

Public Wi-Fi networks in airports, cafes, and railway stations have been used in multiple phishing and interception incidents globally. In India, there have been reported cases of attackers setting up fake Wi-Fi hotspots near banks and offices.

Additionally, phishing-based MITM techniques have been used to steal OTPs and login credentials from Indian users.

4.5 Mitigation and Prevention

Use HTTPS (SSL/TLS encryption)

Avoid public Wi-Fi for financial transactions

Use VPN on public networks

Enable multi-factor authentication (MFA)

Implement certificate pinning in applications

Regular network monitoring

Government initiatives like awareness campaigns by RBI and CERT-In help educate users about such risks.

5. Spoofing Attacks
5.1 What is Spoofing?

Spoofing is when an attacker disguises themselves as a trusted entity by falsifying data.

Common types include:

IP Spoofing

Email Spoofing

ARP Spoofing

DNS Spoofing

5.2 How It Works

In IP spoofing:

Attacker modifies the source IP address in packets.

The target system believes traffic is coming from a trusted source.

This can be used in DDoS or bypassing access controls.

In email spoofing:

Attacker sends an email that appears to come from a legitimate organisation.

User trusts it and clicks malicious links.

Sensitive data is compromised.

5.3 Impact

Phishing scams

Financial fraud

Corporate data breaches

Reputation damage

In India, email spoofing has been widely used in:

Fake income tax refund emails

Fake bank KYC update emails

Job offer scams

5.4 Real-World Example (India-Centric)

There have been multiple phishing campaigns impersonating:

SBI

HDFC Bank

Income Tax Department

UIDAI

Users receive emails or SMS messages asking for account details or OTPs.

5.5 Mitigation and Prevention

Implement SPF, DKIM, and DMARC for email authentication

Use anti-spam filters

Network ingress and egress filtering

User awareness training

Strong authentication mechanisms

Indian organisations must comply with IT Act 2000 and data protection standards to reduce such risks.

6. Role of CERT-In and Indian Regulations

In India, network security governance is supported by:

CERT-In (Indian Computer Emergency Response Team)

IT Act 2000

RBI Cyber Security Framework (for banks)

Data protection guidelines

CERT-In regularly issues advisories regarding DDoS, phishing, and ransomware attacks.

Organisations are required to report certain cyber incidents within a specific time frame.

7. Preventive Strategy for Organisations

Based on my research, a strong network security strategy should include:

Firewalls and IDS/IPS

Regular penetration testing

Security audits

Employee awareness training

Multi-factor authentication

Regular patch updates

Network segmentation

Secure configuration management

Small and medium enterprises (SMEs) in India must also invest in cyber security as they are increasingly becoming targets.

8. Conclusion

Through this research, I have understood that network security threats are not theoretical concepts but real and evolving dangers. In the Indian context, where digital services are expanding rapidly, the risk exposure is high.

Denial of Service attacks can disrupt critical services.
Man-in-the-Middle attacks can compromise financial transactions.
Spoofing attacks can lead to phishing and identity theft.

Prevention requires:

Technical safeguards

Strong policies

Regulatory compliance

User awareness

As an intern, this research has helped me appreciate the importance of proactive cyber security practices. I now understand that network security is not only a technical issue but also a business and national security concern.

9. References

CERT-In Official Advisories

RBI Cyber Security Framework

OWASP Documentation

NIST Cybersecurity Framework


Various cyber security case studies and news reports
