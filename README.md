**GRC-CIA-Triad-Protection-Write-up**

The following is a brief write-up on some questions that may be asked during a cybersecurity audit. It is followed with some suggestions to help with data confidentiality, integrity, and availability.

**CIA Audit questions and suggestions**

Governance, Risk, & Compliance:

The importance of the CIA Triad in data protection.

Problem:

You are tasked with conducting an early assessment of a company's project using the CIA triad to ensure that the Word document's confidentiality, integrity, and availability are held to an acceptable standard.

What questions would you ask?

What recommendations can be applied?

The CIA Triad is widely used within the cyber community, and rightfully so. Confidentiality, Integrity, and availability are imperative to protect any company or individual in today's ever-evolving cyber domain.

Questions to be asked to the stakeholders of a company:

Confidentiality:

1. Who has access to the data?
2. Is encryption used to store and transfer data? 
3. If so, what methods are used? Symmetric or Asymmetric (eg. AES256 or Rivest-Shamir-Adleman (RSA))
4. Is the data in question password protected? If so, who knows the password?
5. What are the read, write, and execute restrictions
6. Are restrictions in place to prevent copying the file to an external drive?
7. Are controls in place to prevent uploading the file to a website or sending the file in an email?

Integrity:

1. Are regular backups conducted? If so, are they tested post-backup?
2. What are the Read, Write, & Execute controls preventing modification to the file?
3. Are changes documented in a log? (eg. V1, V1.5, V2.0)

Availability: 

1. Are there accurate backups of the data? 
2. Was a disaster recovery test performed? 
3. If the cloud is being utilized, is redundancy set up in the event of a point of failure on-prem?
4. Patch Management
5. DDoS Protection
6. Load Balancing

Solutions to protect the CIA Triad and your data:

1. Due to the use of private and public keys, I suggest asymmetric data encryption. RSA, for example.
2. Individual passcodes should be used for all those on a confidential  project. This will ensure nonrepudiation if the document is altered. 
3. Adopt the least privilege and zero trust mentality on all sensitive information.
4. Ensure redundancy is set up in the cloud in case of catastrophe. Data will be available at a different location.
5. Use and enforce a cybersecurity framework such as NIST 800 or ISO 27001 to protect the data's confidentiality, Integrity, and availability.
6. Employee training on the importance of safeguarding data and what to look out for in the event of an attack.


