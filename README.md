# Third-Party Risk Management (TPRM)

## Overview

This project documents a third-party risk assessment of a Software-as-a-Service (SaaS) provider offering an application for scientific data analysis. The assessment is based on a completed TPRM questionnaire and focuses on identifying cybersecurity deficiencies that could expose "my" organization to risk. The controls in that questionnaire are taken from the NIST Framework.

The review examines the supplier's cybersecurity capabilities, vulnerability management, detection and monitoring, incident response, identity and access management, and data loss prevention. The findings are assessed for their potential impact on the customer organization and summarized for escalation to senior management.

## Scenario

Synveta is a mid-sized, R&D-intensive company that relies on a SaaS application developed by Zynilo Labs, a start-up, to analyze scientific data. Because the service supports scientific data analysis and may involve sensitive information, the supplier's cybersecurity capabilities are important to Synveta's overall risk exposure.

As part of its third-party risk management process, Synveta has already identified and classified its suppliers into risk tiers. Zynilo Labs is classified as a Tier 1 supplier due to the importance of the service it provides.

The task here is to review Zynilo Labs' responses to a TPRM questionnaire, identify any cybersecurity deficiencies, and determine which risks should be brought to senior management's attention. My assessment focuses on the supplier's security controls and capabilities rather than conducting a technical assessment of the SaaS application itself. A technical assessment of the SaaS application is thus outside the scope of this project. 

Synveta also relies on a separate cloud service provider. The security posture of that provider was outside the scope of this assessment, which focused exclusively on Zynilo Labs. Dependencies on subcontractors and underlying cloud services would need to be examined separately where relevant to the overall risk exposure.

## Assessment Approach

I reviewed the completed TPRM questionnaire provided by Zynilo Labs and assessed the supplier's cybersecurity controls and capabilities.

The assessment focused on identifying control deficiencies, evaluating their potential impact on Synveta, and determining which findings warranted escalation to senior management. Individual findings were considered in the context of the supplier's overall security posture, including how weaknesses across different control areas could combine to increase risk.

The results were documented in a risk assessment and a set of recommendations to senior management.

## Key Findings

The assessment identified five high-risk areas and one medium-risk area in Zynilo Labs' cybersecurity controls and capabilities.

### High Risk

**1. Cybersecurity Governance and Capabilities**

Zynilo Labs has no dedicated cybersecurity personnel and does not follow an established cybersecurity framework. This raises concerns about the supplier's ability to establish, maintain, and oversee effective security controls.

**2. Vulnerability Management**

The supplier has no vulnerability management program and has neither completed nor planned penetration testing. This limits its ability to identify and address security weaknesses in a systematic manner.

**3. Detection and Monitoring**

Zynilo Labs lacks the capability to detect and monitor security events, both internally and through a Managed Security Service Provider (MSSP). Potential security incidents may therefore go undetected.

**4. Incident Response**

The supplier lacks the capability to respond effectively to cybersecurity incidents. Without an established incident response capability, its ability to contain incidents and limit their impact is a significant concern.

**5. Identity and Access Management (IAM)**

The supplier lacks several important access controls, including least privilege, role-based access control (RBAC), and periodic access reviews. Although individual deficiencies vary in severity, their combined effect creates a significant weakness in identity and access management. This is assessed as a high risk by me.

### Medium Risk

**6. Data Loss Prevention (DLP)**

Zynilo Labs lacks data loss monitoring capabilities. However, data encryption and backups are in place, providing some protection against data exposure and loss. The overall risk is therefore assessed as medium rather than high.

## Risk Assessment

Risk ratings were based on the severity of identified control deficiencies and their potential impact on Synveta. The assessment considered the relevance of existing safeguards and the combined effect of related control weaknesses. The ratings represent my analytical judgment within the scope of this exercise and should not be interpreted as independently validated risk scores.

Five areas were classified as high risk: cybersecurity governance and capabilities, vulnerability management, detection and monitoring, incident response, and identity and access management.

The IAM findings illustrate the importance of assessing controls both individually and collectively. 
- Lack of least privilege leads to bigger consequences of compromised accounts.
- Lack of role-based access control makes it harder to control user privileges.
- Lack of periodic access reviews enables inappropriate access rights to remain in the system.
- Lack of separation of duties enables conflation of access rights, permissions and responsibilities.

The overall risk these deficiencies represent a significant weakness in access management when taken together, and therefore I classified them as high risk overall.

The lack of data loss monitoring was classified as medium risk because encryption and backups were in place. These safeguards reduce some of the potential impact, although they do not eliminate the risks associated with inadequate data loss monitoring.

The overall supplier relationship was assessed as high risk to Synveta because the SaaS application is used for scientific data analysis involving sensitive data, while the supplier has significant weaknesses in its cybersecurity capabilities.

## Recommendations

The findings indicate that Synveta should treat its relationship with Zynilo Labs as a significant third-party risk and escalate the assessment to senior management.

I recommend that Synveta:

- **Address the supplier's cybersecurity capabilities:** Raise the absence of dedicated cybersecurity personnel and an established security framework with Zynilo Labs, and request a credible plan for improving its security practices.
- **Prioritize vulnerability management:** Seek evidence of a systematic vulnerability management process and appropriate security testing, including penetration testing.
- **Establish detection and incident response capabilities:** Require clarity on how security events will be detected, investigated, and handled, including whether external security services are needed.
- **Strengthen identity and access management:** Prioritize least privilege, role-based access control, periodic access reviews, and appropriate separation of duties.
- **Review data protection measures:** Address the lack of data loss monitoring and determine whether the existing encryption and backup measures provide sufficient protection for the data handled by the service.
- **Review the supplier relationship:** Assess whether the current level of risk is acceptable, taking into account the sensitivity of the data, the supplier's contractual security obligations, and its ability to address the identified deficiencies.

These recommendations are intended to support management decisions about risk treatment, supplier follow-up, and the conditions under which the relationship should continue.

## What I Learned

This project gave me practical experience in reviewing a third-party security questionnaire, identifying control deficiencies, and translating technical and organizational weaknesses into business risks.

One important lesson was that individual control deficiencies cannot always be assessed in isolation. In the IAM assessment, several medium- and low-risk findings combined to create a high-risk issue.

I also learned to consider existing safeguards when assessing risk. The presence of encryption and backups affected the DLP risk rating, even though data loss monitoring was absent.

Finally, the assessment reinforced the importance of connecting a supplier's security posture to the customer organization's exposure. The objective of a TPRM assessment is not simply to list missing controls, but to help decision-makers understand the implications and determine what action is warranted.

## Original Exercise and Context

This assessment originated as a practical exercise within GRC Mastery certification. The exercise involved reviewing a completed third-party risk questionnaire for a SaaS provider used by a fictional research organization and identifying significant cybersecurity risks for escalation to senior management.

I completed the assessment by reviewing the questionnaire responses given to me, classifying the identified risks, and preparing recommendations for senior management. The work presented in this portfolio reflects my own analysis and conclusions.

For this portfolio project, the scenario uses the fictional organizations Synveta and Zynilo Labs. The supporting questionnaire has been shortened for privacy purposes, and the assessment and recommendations are documented in the accompanying files.

## Supporting Documentation

The project includes two supporting documents:

- **TPRM Questionnaire (Anonymized):** The supplier's completed questionnaire used as the basis for my assessment. Identifying information has been replaced with asterisks, and the comment column has been cleared to separate the supplier's responses from my analysis.

View the TPRM Questionnaire: [TPRM Questionnaire (Anonymized)](https://github.com/Henrik-Nordlund/Third-Party-Risk-Management/blob/main/TPRM_Questionnaire_Anonymized.xlsx)

- **Recommendations to Senior Management:** My original Word document presenting my risk findings, assessment of the supplier's cybersecurity deficiencies, and conclusions regarding the risks to the customer organization.

View my recommendation draft: [Recommendations to senior management regarding Zynilo Labs](https://github.com/Henrik-Nordlund/Third-Party-Risk-Management/blob/main/Recommendations%20to%20senior%20management%20regarding%20Zynilo%20Labs.docx)

