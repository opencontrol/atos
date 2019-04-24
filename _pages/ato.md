---
title: Lifecycle of a Launch
---

Every federal information system must go through NIST's [Risk Management Framework](steps/) before it can be used to process federal information. This process culminates in a signed Authority to Operate (ATO) being issued. Because the ATO process is a complex, multi-step process which will constrain the design and implementation of your system, you should start thinking about how it applies to your system _before_ you begin designing and implementing it.

### Key roles

- **Authorizing Official (AO)** The AO is ultimately responsible for determining if the risk of operating the system is acceptable, and if so, issuing an Authority to Operate (ATO) for that system.
- **System Owner** The system owner is usually the product lead or tech lead of the project team. They will be named in the ATO documents and are the main contact during the evaluation process that leads up to an ATO.

### Definitions

- **Information system** means a discrete set of information resources organized for the collection, processing, maintenance, use, sharing, dissemination, or disposition of information ([44 U.S.C. § 3502](https://www.law.cornell.edu/uscode/text/44/3502#8)).

### Team

ATO Sprints are staffed by cross-divisionally. Beyond the project team roles (ex: system owner, product owner, etc) ATO Sprint roles typically include:

- **Authorizing Official (AO)**: Responsible for overall impact categorization and risk acceptance.
- **Information System Security Officer (ISSO)**: Supports the information security system, consults on control selection, organizes scanning process. Reports to the Information System Security Manager (ISSM).
- **Penetration tester(s)**: Conducts the penetration test after terms are agreed to as documented in the Rules of Engagement (RoE).
- **Assessor**: Validates and verifies that the documented controls (see [Step 3](#step-3--document-the-controls)) actually work, using the assessment cases (see [Step 4](#step-4--assess-the-controls)).

### Steps

See [Background](../steps/).

### Re-authorization

Your system may need to be reassessed and re-authorized if your application team is planning to make substantive changes, such as changes to:

- Encryption methodologies
- Administrative functionality within the application
- The kinds of information you store (for example, [personally identifiable information (PII)](../privacy/))
- The external services used or how/what data flows to/from them
- Anything that will requires an update to the System Security Plan, system diagram, etc.

Example changes that do _not_ require re-authorization, as long as they don't include the above:

- Features
- Bug fixes
- Interface changes
- Documentation updates

The Authorizing Official determines whether a system needs re-authorization. If you're planning a change that you think may require re-authorization, contact them.

If it needs re-authorization, follow the usual steps for getting an ATO. You should be able to reuse most of your existing ATO materials, assuming they have been kept up-to-date.

### ATO renewal

If your current ATO is going to expire, you'll need the ATO to be renewed. Follow the usual steps for getting an ATO. You should be able to reuse most of your existing ATO materials, assuming they have been kept up-to-date.
