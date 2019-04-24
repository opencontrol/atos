---
title: Overview
---

Every federal information system must go through NIST's [Risk Management Framework](steps/) before it can be used to process federal information. This process culminates in a signed Authority to Operate (ATO) being issued. Because the ATO process is a complex, multi-step process which will constrain the design and implementation of your system, you should start thinking about how it applies to your system _before_ you begin designing and implementing it.

### Definitions

- **Information system** means a discrete set of information resources organized for the collection, processing, maintenance, use, sharing, dissemination, or disposition of information ([44 U.S.C. § 3502](https://www.law.cornell.edu/uscode/text/44/3502#8)).

### Roles

Roles in ATO processes typically include:

- **Assessor**: Validates and verifies that the documented controls (see [Step 3](../steps/#step-3-implement-security-controls)) actually work, using the assessment cases (see [Step 4](../steps/#step-4-assess-security-controls)).
- **Authorizing Official (AO)**: Responsible for overall impact categorization and risk acceptance. The AO is ultimately responsible for determining if the risk of operating the system is acceptable, and if so, issuing an Authority to Operate (ATO) for that system.
- **Information System Security Officer (ISSO)**: Supports the information security system, consults on control selection, organizes scanning process. Reports to the Information System Security Manager (ISSM).
- **Penetration tester(s)**: Conducts the penetration test after terms are agreed to as documented in the Rules of Engagement (RoE).
- **System Owner** The system owner is usually the product lead or tech lead of the project team. They will be named in the ATO documents and are the main contact during the evaluation process that leads up to an ATO.

The long version: [NIST SP 800-37r2 Appendix D](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-37r2.pdf#page=133)

### FISMA

In the Federal government, the principal law governing the security of information systems is the **Federal Information Security Management Act (FISMA)**. For more information on FISMA, check out the [FISMA Ready introduction](https://github.com/fisma-ready/introduction).

One of the goals of the Federal Information Security Management Act of 2002 (FISMA) is to “provide a comprehensive framework for ensuring the effectiveness of information security controls over information resources that support Federal operations and assets.” The National Institute of Standards and Technology (NIST) was tasked with designing and implementing this framework: the result is NIST’s Risk Management Framework (RMF). All federal information and information systems (except classified information and national security systems) are subject to NIST’s RMF. There's [an introduction to the RMF on NIST's website](http://csrc.nist.gov/groups/SMA/fisma/framework.html). A more comprehensive guide, including how to apply the framework, references to the various relevant publications, and definitions of roles and responsibilities, is found in NIST's [Special Publication 800-37](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-37r1.pdf).

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
