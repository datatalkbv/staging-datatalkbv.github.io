# Security Policy
## DataTalk BV

**Last Updated: September 10, 2024**

## 1. Introduction

At DataTalk, headquartered in Belgium, we understand the critical importance of data security, privacy, and European data residency in the legal industry. Our AI-powered legal research, drafting, and review platform is designed with robust security measures to protect your sensitive information and ensure compliance with relevant European standards. This policy outlines our commitment to maintaining the highest levels of security and data protection within the European context.

## 2. Infrastructure and Hosting

### 2.1 Amazon Web Services (AWS) in Europe

DataTalk exclusively uses Amazon Web Services (AWS) for our hosting infrastructure. All our servers are located in the eu-west-3 (Paris) region, ensuring data residency within the European Union.

### 2.2 AWS Compliance and European Certifications

The AWS Europe (Paris) Region complies with numerous international and European standards, including:

- ISO 27001, ISO 27017, ISO 27018
- SOC 1, SOC 2, and SOC 3 Security & Availability
- PCI DSS Level 1
- Hébergeur de Données de Santé (HDS) certification
- Compliance with GDPR requirements

### 2.3 European Data Residency

- All client data is processed and stored exclusively within the European Union.
- We ensure that data does not leave the EU unless explicitly requested and authorized by the client.

### 2.4 Availability and Redundancy within Europe

Our infrastructure leverages AWS's three Availability Zones (AZs) in the Paris region, providing high availability and disaster recovery capabilities within the EU.

## 3. Data Protection

### 3.1 Encryption

#### 3.1.1 Data at Rest
- All data stored in our systems is encrypted using AES-256 encryption.
- Encryption keys are managed using AWS Key Management Service (KMS) with regular key rotation.

#### 3.1.2 Data in Transit
- All data transmitted between our servers and clients is encrypted using TLS 1.2 or higher.
- We enforce HTTPS for all connections, with HTTP Strict Transport Security (HSTS) enabled.

### 3.2 Access Control

- Multi-factor authentication (MFA) is mandatory for all user accounts.
- Role-based access control (RBAC) is implemented to ensure users only have access to data they need.
- Regular access reviews are conducted to maintain the principle of least privilege.
- Unique user accounts are required to ensure traceability of actions.

### 3.3 Password Policy

- Minimum password length of 12 characters
- Passwords must contain characters from at least three of the following categories: uppercase letters, lowercase letters, numbers, and non-alphanumeric characters
- Password history is enforced to prevent reuse of the last 12 passwords
- Passwords are communicated securely to new users
- Password strength meters are implemented to encourage strong passwords

### 3.4 Device Security

- Hard drives in user PCs and servers are encrypted using industry-standard encryption
- Antivirus software with real-time scanning is installed on all devices, with weekly full system scans
- Operating systems and key business applications are updated monthly with security patches
- Mobile Device Management (MDM) solutions are implemented for company-owned devices

## 4. Network Security

- Next-generation firewalls and intrusion detection/prevention systems are in place to monitor and protect our network
- Regular vulnerability scans and penetration tests are conducted quarterly
- Virtual Private Network (VPN) with multi-factor authentication is required for remote access
- Network segmentation is implemented to isolate critical systems and data

## 5. Email Security

- Advanced email protection solutions scan all inbound and outbound emails for spam, malware, and phishing attempts
- We implement Exchange Online Protection and Advanced Threat Protection for Microsoft 365 users
- Regular phishing simulation exercises are conducted to test and train employees

## 6. Data Retention and Destruction

- We have a formal, documented data retention policy compliant with European regulations
- Client data is retained only for the duration necessary to provide our services
- Secure data destruction methods are used for both electronic and physical media, in compliance with EU data protection standards
- Data destruction certificates are provided upon request

## 7. Incident Response and Disaster Recovery

- A comprehensive, documented incident response plan is in place, covering various scenarios including data breaches
- Our disaster recovery plan ensures business continuity with defined Recovery Time Objectives (RTO) of 4 hours and Recovery Point Objectives (RPO) of 1 hour
- Clients are notified of any confirmed data breaches within 72 hours, in accordance with GDPR requirements
- Regular backups are performed and stored within the European Union
- Annual incident response drills are conducted to test the effectiveness of our plans

## 8. Vendor Management

- We maintain a robust vendor management program to ensure third-party service providers adhere to our security standards and European data protection regulations
- Vendors with access to sensitive data are required to maintain relevant security certifications (e.g., ISO 27001, SOC 2 Type II)
- Annual security assessments are conducted for critical vendors
- Vendor contracts include specific clauses related to data protection and GDPR compliance

## 9. Employee Security

- Background checks are conducted on all employees in accordance with Belgian and EU law
- Mandatory security awareness training is conducted for all staff upon hiring and annually thereafter, with a focus on European data protection regulations
- Employees sign confidentiality agreements and adhere to a strict code of conduct
- Quarterly security newsletters are distributed to keep employees informed about current threats and best practices

## 10. Compliance

- Our platform is designed to support client compliance with various European regulations, including GDPR
- We regularly review and update our privacy policies to reflect current EU legal requirements
- A designated Data Protection Officer oversees our compliance efforts
- Annual GDPR audits are conducted to ensure ongoing compliance
- We maintain records of processing activities as required by GDPR Article 30

## 11. Client Controls and Transparency

- Clients have access to security logs related to their account activities
- A client portal is provided for managing user permissions and access controls
- Regular security reports are available to clients upon request
- Clients can request and receive data export in a machine-readable format

## 12. Continuous Improvement

We are committed to continuously improving our security posture. This includes:

- Regular review and update of all security policies and procedures
- Staying informed about emerging threats and evolving best practices in the European context
- Incorporating client feedback into our security program
- Participating in industry security forums and collaborative threat intelligence sharing platforms

## 13. Physical Security

- Access to our offices is controlled using electronic access cards and biometric authentication
- Visitors must sign in and be escorted at all times
- CCTV surveillance is in place at all entry and exit points
- Server rooms are protected with additional security measures, including separate access controls and environmental monitoring

## 14. Secure Development Practices

- We follow a secure software development lifecycle (SDLC) methodology
- Regular code reviews and static code analysis are performed
- All code changes go through a formal change management process
- Production and development environments are strictly separated
- We conduct regular security testing, including dynamic application security testing (DAST) and interactive application security testing (IAST)

## 15. Asset Management

- We maintain a comprehensive inventory of all hardware and software assets
- Regular audits are conducted to ensure accuracy of the asset inventory
- End-of-life and end-of-support dates are tracked for all assets
- A formal process is in place for securely disposing of assets at the end of their lifecycle

## 16. Contact Information

For any security-related questions or to report a security concern, please contact our security team at mail@datatalk.be or through our dedicated security hotline: +32 473 57 62 62.

At DataTalk, we are committed to maintaining the highest standards of security and compliance within the European legal and regulatory framework. We continuously review and enhance our security measures to protect your valuable legal data and ensure the integrity of our AI-powered legal services platform, all while maintaining strict data residency within the European Union.