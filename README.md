Crestview | Privileged Access & Access Control Risk Assessment
GRC Portfolio Project · Risk Assessment · Security Governance
Executive Overview
This project demonstrates a structured Governance, Risk and Compliance (GRC) assessment of privileged access and access-control arrangements within the Crestview case study.
The assessment examines weaknesses in the management, protection, and monitoring of administrative access. It documents identified risk areas, evaluates their potential impact, proposes risk treatment measures, and establishes supporting policy requirements.
The project brings together three complementary artefacts:
•	A GRC Risk Assessment Workbook for risk identification, analysis, and treatment tracking.
•	An Executive Risk Report for communicating risk exposure and remediation priorities to senior management.
•	A Privileged Access and Access Control Policy defining the required control environment and access governance principles.
The overall objective is to demonstrate how technical access-control weaknesses can be translated into structured risk analysis, actionable remediation, and management-level governance.
________________________________________
Project Objectives
The assessment was developed to:
•	Identify weaknesses in privileged access and access-control arrangements.
•	Assess the potential business and security impact of identified risks.
•	Establish risk priorities using structured assessment methods.
•	Document proposed risk treatment and remediation activities.
•	Define access-control requirements through a supporting policy.
•	Communicate risk exposure and recommendations to senior management.
•	Support accountability through risk ownership, remediation tracking, and governance reporting.
Repository Structure
Artefact	Purpose
GRC_Crestview_Risk_Assessment.xlsx	Risk register, risk treatment tracker, quantitative risk assessment calculator, risk matrix, and dashboard material.
Crestview Privileged Access Policy.pdf	Policy requirements for privileged access, access authorisation, authentication, monitoring, and review.
Crestview Executive Risk Report	Management-level summary of risk posture, top risks, control gaps, remediation priorities, and residual concerns.

Assessment Scope
The assessment focuses on privileged access and access-control governance, including:
•	Privileged account management
•	Administrative authentication and MFA
•	Access authorisation and least privilege
•	Shared administrator accounts
•	Privileged access reviews and recertification
•	Temporary and time-bound access
•	Service-account governance
•	Privileged activity logging and monitoring
•	Centralised security monitoring and alerting
•	Third-party privileged access
•	Access-control policy and exception management
Key Risk Themes
The assessment identifies elevated exposure associated with weaknesses in privileged access controls.
Risk Area	Risk Consideration
Privileged Account Compromise	Shared administrative credentials and limited PAM capability may increase the risk of unauthorised privileged access.
Unauthorised Privileged Access	Inconsistent MFA may increase exposure to compromised administrative credentials.
Excessive Privileges	Users may retain permissions beyond their business requirements.
Insufficient Monitoring	Gaps in centralised logging and alerting may delay detection and investigation.
Uncontrolled Temporary and Service Access	Privileges or service accounts may remain active or inadequately protected.
These risk themes form the basis of the proposed treatment actions and management recommendations.

Risk Assessment & Treatment
The assessment uses a structured approach to document and manage risk:
1.	Identify the risk and relevant control weakness.
2.	Assess potential likelihood and business impact.
3.	Determine the risk rating and priority.
4.	Identify an appropriate risk treatment.
5.	Define recommended controls and remediation actions.
6.	Establish ownership and target dates.
7.	Track remediation through the GRC process.
8.	Review residual risk and outstanding concerns.
Quantitative Risk Assessment
The workbook includes quantitative risk assessment concepts to support the estimation of potential financial exposure.sa
Metric	Definition	Calculation
AV	Asset Value	Estimated value of the affected asset
EF	Exposure Factor	Estimated proportion of asset value lost
SLE	Single Loss Expectancy	AV × EF
ARO	Annual Rate of Occurrence	Estimated frequency of an event per year
ALE	Annual Loss Expectancy	SLE × ARO

Executive Risk Reporting
The Executive Risk Report translates assessment findings into management-level information to support prioritisation and governance.
The report covers:
•	Overall risk posture
•	Top five privileged-access risks
•	Major control gaps
•	Recommended remediation activities
•	Immediate and medium-term priorities
•	Residual risk considerations
•	Management conclusion
Remediation Priorities
Immediate — 0 to 90 days
•	Establish a complete inventory of privileged, shared, and service accounts.
•	Enforce MFA for privileged and administrative access.
•	Remove unnecessary and excessive permissions.
•	Establish individual administrator accounts wherever possible.
•	Introduce formal approval and expiry requirements for temporary access.
•	Identify legacy systems that cannot currently support required controls.
Medium Term — 3 to 6 months
•	Implement a Privileged Access Management (PAM) solution.
•	Establish formal quarterly privileged-access reviews.
•	Strengthen service-account ownership and credential management.
•	Implement appropriate privileged-session monitoring and recording.
•	Integrate critical systems with centralised SIEM monitoring.
Ongoing Governance
•	Monitor privileged activity and investigate suspicious events.
•	Track control gaps and remediation through the GRC process.
•	Escalate overdue or high-risk actions to the appropriate governance committee.
•	Review residual risks and formally document accepted exceptions.
________________________________________
Privileged Access & Access Control Policy
The supporting policy establishes the expected control environment for managing access to systems and sensitive information.
Core Control Principles
Authorise → Limit → Authenticate → Monitor → Review → Remove
The policy addresses:
•	Secure management and rotation of privileged credentials
•	Least-privilege access
•	Appropriate manager or system-owner approval
•	MFA for privileged and administrative accounts
•	Restricted and regularly reviewed administrative access
•	Time-bound temporary access
•	Quarterly privileged-access reviews
•	Prompt access changes for joiners, movers, and leavers
•	Avoidance of shared accounts, or compensating controls where necessary
•	Logging and monitoring of privileged activity
•	Service-account ownership and governance
•	Approved and monitored third-party access
•	Documented, risk-assessed, and approved policy exceptions
The policy also establishes enforcement expectations and requires periodic review, including following significant changes or access-control incidents.

Management Recommendations
The assessment recommends strengthening the privileged-access control environment through a coordinated approach:
PAM → MFA → Least Privilege → Access Reviews → Monitoring
These controls should operate together to reduce the likelihood of credential compromise, limit unauthorised access, improve accountability, and support timely detection of suspicious privileged activity.
Remediation should be supported by:
•	Clearly assigned risk and control owners
•	Defined remediation deadlines
•	Measurable control outcomes
•	Documented residual risks
•	Formal risk acceptance where appropriate
•	Regular reporting through established GRC governance processes

Skills & Competencies Demonstrated
This project demonstrates practical application of:
•	Governance, Risk and Compliance (GRC)
•	Risk identification and assessment
•	Likelihood and impact analysis
•	Quantitative risk assessment concepts
•	Risk treatment and remediation planning
•	Privileged Access Management
•	Identity and access governance
•	Security policy development
•	Executive risk reporting
•	Risk ownership and remediation tracking
•	Security-control documentation
•	Management and governance communication

Scope & Limitations
•	This project is a portfolio case study and is not a formal audit, certification, or independent assurance report.
•	Risk ratings and financial estimates depend on the assumptions documented in the assessment.
•	Recommended controls represent proposed improvements; the artefacts do not independently demonstrate implementation or operating effectiveness.
•	The assessment does not establish attribution to a confirmed individual or threat actor.
•	Confidential, personal, or organisation-sensitive information should be reviewed and anonymised before public publication.

