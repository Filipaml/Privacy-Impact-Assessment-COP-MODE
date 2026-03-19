# Privacy Impact Assessment (PIA) - COP-MODE Project

This repository as a detailed Privacy Impact Assessment of the COP-MODE data collection project. Developed for the Security and Privacy course (2nd year) at the Faculty of Sciences(FCUP).


## Project Overview
The COP-MODE project involves collecting sensitive personal data via smartphones from participants over a one-week period. As the PII Controller and Processor, we identified and mitigated risks associated with handling Personally Identifiable Information (PII) to ensure compliance with privacy standards.


## Data Collection & Sensitivity
The system gathers various types of information, categorized by their privacy impact:

**Personally Identifiable Information (PII):** Participant email addresses used for communication and coordination.

**Sensitive Data:** Continuous GPS location, application usage patterns (names and time spent), and nearby device identifiers.


## Risk Assessment Methodology
Using the CNIL PIA Tool, we conducted a two-stage evaluation:

**1. Initial "Plain Setup" Analysis**

In a scenario without any security measures, we identified critical vulnerabilities:

Illegitimate Access: High likelihood of unauthorized viewing of movements and social connections

Unwanted Modification: Potential for data integrity breaches during transmission

Data Disappearance: Risks of permanent loss due to system failures or human error

Result: All risk categories were positioned in the high-risk zones

**2. Mitigation & Action Plan**

To reduce these risks to acceptable levels, we implemented several Privacy by Design measures:

Encryption: All sensitive data is encrypted at rest and in transit to protect against interception.

Access Control: Role-based access restricts data to authorized team members on a "need-to-know" basis.

Anonymization & Pseudonymization: Techniques applied to email addresses and application names to prevent direct linkability.

Data Isolation & Segmentation: Storing sensitive datasets in separate, isolated databases to prevent cross-correlation and limit the impact of potential leaks.

## Conclusion
The re-assessment confirmed that the implementation of these corrective measures successfully reduced both the likelihood and severity of all identified privacy risks, ensuring a secure environment for participant data.

Made by: Filipa Melo Leite & Francisca Macedo
