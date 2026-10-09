Risk Assessment – hur mina findings klassificerades.  
Recommendations – vad resultaten innebär för kundorganisationen.  
What I Learned – vad projektet faktiskt gav mig.  
Original Exercise – GRC Mastery och transparent kontext.  
Supporting Documentation – questionnaire + recommendation document.

# Third-Party Risk Management (TPRM)

## Overview

This project documents a third-party risk assessment of a Software-as-a-Service (SaaS) provider offering an application for scientific data analysis. The assessment is based on a completed TPRM questionnaire and focuses on identifying cybersecurity deficiencies that could expose "my" organization to risk. The controls in that questionnaire are taken from the NIST Framework.

The review examines the supplier's cybersecurity capabilities, vulnerability management, detection and monitoring, incident response, identity and access management, and data loss prevention. The findings are assessed for their potential impact on the customer organization and summarized for escalation to senior management.

## Scenario

Synveta is an midsize R&D intensive company that relies on a SaaS application developed by Zynilo Labs, a start-up, to analyze scientific data. Because the service supports scientific data analysis and may involve sensitive information, the supplier's cybersecurity capabilities are important to Synveta's overall risk exposure.

As part of its third-party risk management process, Synveta has already identified and classified its suppliers into risk tiers. Zynilo Labs is classified as a Tier 1 supplier due to the importance of the service it provides.

The task here is to review Zynilo Labs' responses to a TPRM questionnaire, identify any cybersecurity deficiencies, and determine which risks should be brought to senior management's attention. My assessment focuses on the supplier's security controls and capabilities rather than conducting a technical assessment of the SaaS application itself. A technical assessment of the SaaS application is thus outside the scope of this project. In addition, Synveta has much data in the cloud, utlitizing one of the big vendors from the US for this. That is out-of scope for this assessment.


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

