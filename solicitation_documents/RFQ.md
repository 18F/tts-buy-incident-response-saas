**General Services Administration**

Federal Acquisition Service

Technology Transformation Services

1800 F St NW \| Washington, DC \| 20405

# Request for Quotation

Solicitation Number

TCTOA-18-0014

**From:** Michelle McNellis, Contracting Officer, GSA TTS

**Subject:** Request for Quotation (RFQ)

**Date:** August 21, 2018

**Reply By:** **August 31, 2018** **4:00 pm EST**

**Document Type:** Combined Synopsis/Solicitation Solicitation

**NAICS Code:** 541519 – Other Computer Related Services

**Authority:** The solicitation document and incorporated provisions and clauses are those in effect through Federal Acquisition Regulation (FAR) subpart 12.6 Streamlined Procedures for Evaluation and Solicitation for Commercial Items with supplementing information from FAR subpart 13.106 Soliciting Competition, Evaluation of Quotations or Offers, Award and Documentation

Contents
========
- [1.0 Instructions](#10-instructions)
- [2.0 Background](#20-background)
- [3.0 Requirements](#30-requirements)
- [4.0 Basis for Award](#40-basis-for-award)
- [5.0 Evaluation Process](#50-evaluation-process)
- [6.0 Period of Performance](#60-period-of-performance)
- [7.0 Type of Contract](#70-type-of-contract)
- [8.0 Invoicing](#80-invoicing)
- [9.0 Administration](#90-administration)
- [10.0 TTS Transparency Policy](#10-tts-transparency-policy)
- [11.0 Clauses](#11-clauses)

1.0 Instructions
================

Technology Transformation Services’ (TTS) Office of Acquisition (OA) hereby issues this Request for Quotation (RFQ), under Federal Acquisition Regulation subpart 12.6 Streamlined Procedures for Evaluation and Solicitation for Commercial Items with supplementing information from FAR subpart 13.106 Soliciting Competition, Evaluation of Quotations or Offers, Award and Documentation for obtaining a Software-as-a-Service (SaaS) that will provide full visibility into any potential issues and incidents that may arise within the applications utilizing the SaaS along with notifications that will allow for timely responses.

The vendor shall submit a quotation in accordance with the instructions, terms, and conditions of this RFQ. The government intends to award the order based on initial quotations. Therefore, it is critical your initial submission is for your best quotation and that you are fully responsive to the RFQ.

Unless expressly authorized by the RFQ, any quoter planning to make an exception to a term or condition of the RFQ should consult with the Contracting Officer (CO) in writing before submitting a quotation.

NOTE: This RFQ is being posted using FAR 52.232-18 Availability of Funds. This award will not be made prior to receipt and acceptance of the funds. See FAR 52.232-18 Availability of Funds (APR 1984) in the Clause Addendum.

1.1 Quote Instructions
----------------------

Quotes will only be accepted via the referenced Google Forms below. The vendor must complete the [Technical Response Google Form](https://goo.gl/forms/74p2CyXLSsVETrzm1) and [Price Response Google Form](https://goo.gl/forms/SakMJFEEjesOE6k93).

1.2 Questions
-------------

Any questions concerning the RFQ must be submitted using [the issue template](https://github.com/18F/tts-buy-incident-response-saas/issues/new) in the associated repository’s [issues tab](https://github.com/18F/tts-buy-incident-response-saas/issues) no later than August 27, 2018, 4:00pm (ET).

1.3 Potential Organizational Conflicts of Interest Statement
------------------------------------------------------------

Every offeror who wishes to be considered for the award shall provide a signed Organizational Conflict of Interest statement with their quotation submission, which describes concisely all relevant facts concerning any past, present, or planned interest (financial, contractual, organizational, or otherwise) relating to the work to be performed under the proposed contract and bearing on whether the offeror has a possible organizational or personal conflict of interest with respect to:

1.  Being able to render impartial, technically sound, and objective assistance or advice; or,

2.  Being given an unfair competitive advantage.

Offerors may also provide relevant facts that show how its organizational structure and/or management systems limit its knowledge of possible organizational conflicts of interest relating to other divisions or sections of the organization and how that structure or system would avoid or mitigate such organizational conflict.

No contract award shall be made until any potential conflict of interest has been neutralized or mitigated to the satisfaction of the CO in accordance with FAR subpart 9.5 [Organizational and Consultant Conflicts of Interest](https://www.acquisition.gov/browsefar). Refusal to provide the requested information or the willful misrepresentation of any relevant information by an offeror shall disqualify the offeror from further consideration for award of a contract under this solicitation. If the CO determines that a potential conflict can be avoided, effectively mitigated, or otherwise resolved through the inclusion of a special contract clause, the terms of the clause will be subject to negotiation.

2.0 Background
==============

TTS has a need for an incident response, notification, and resolution service which can receive alert information from cloud.gov, login.gov, and other projects within TTS. This application should aggregate the information into incidents, and send the appropriate notifications, provide contextual information on these incidents, automatically manage scheduling and escalation, and provide reporting functionality. This functionality is critical to the ability of the various teams to meet their technical mission needs and compliance requirements.

3.0 Requirements
================

3.1 Requirements
----------------

The vendor must provide a SaaS that meets the following requirements:

1.  The ability to send alerts via email, text message, phone, and mobile app push notifications to team members.

2.  Uptime measure that meets or exceeds 99.99% in the last six months.

3.  Must be on the GSA IT Standards Profile, or must commit to going through and passing the GSA IT Standards Profile process before award.

4.  The ability to support multi-factor authentication, with priority for support for Single Sign-On integration that would support GSA Google SSO or GSA SecureAuth SSO.

5.  Customer data must be stored in FedRAMP Authorized infrastructure, with priority for FedRAMP JAB Moderate or High P-ATO. This requirement can be fulfilled in various ways, for example:

    1.  A SaaS that does not have its own FedRAMP Authorization, but it stores data in FedRAMP Authorized IaaS or PaaS services.

    2.  A SaaS that has its own FedRAMP Authorization for the SaaS.

6.  The ability to integrate the SaaS alerting features via API with external monitoring tools including Prometheus, CloudWatch, and New Relic.

7.  Cybersecurity practices such as a vulnerability disclosure program, responsible disclosure policy, or bug bounty program.

3.2 Pagerduty Standard Salient Characteristics
----------------------------------------------

The Technology Transformation Services is currently using Pagerduty Standard, however this solicitation allows for “equal” products to be offered, which will be considered for award (See FAR 52.211-6, Brand Name or Equal in Section 7 below).

Salient characteristics are those particular characteristics that specifically describe the essential physical and functional features of the material or service required. Pagerduty Standard has the following salient characteristics that are firm requirements that an “equal” item must meet to be acceptable for award:

1.  Support for specifying “on call” schedules for team members, so that it will automatically send alerts to the specific team members who have responsibility to respond to those alerts.

2.  The ability to configure detailed schedules for team members, so that primary alerting responsibilities will automatically rotate between team members according to those schedules.

3.  The ability to configure secondary responsibilities team members to receive an escalated alert if the primary responsibility team member does not respond to an alert.

4.  Support for role management with an administrative user who can create multiple isolated “teams” of users.

5.  Support to isolate each team from the other teams, with the ability for each team to assign team-specific roles/permissions to users.

6.  The ability to isolate the operators on our teams such that they are never able to view each other’s alerts or modify each other’s team roles/permissions.

3.3 Deliverables
----------------

The vendor must provide:

-   Up to 35 licenses on an annual license basis;

-   24/7/365 technical support via phone, chat, and email; and,

-   Unlimited data retention.

4.0 Basis for Award
===================

This procurement is being conducted in accordance with FAR subpart 12.6, “Streamlined Procedures for Evaluation and Solicitation for Commercial Items,” as supplemented with additional information included in the RFQ. Technical Factors will be evaluated in accordance with FAR subpart 12.602 “Streamlined Evaluation of Offers”. Price will be evaluated in accordance with FAR subpart 13.106. Provision 52.212-2, Evaluation -- Commercial Items, does not apply to this requirement. The offerors agree to and are bound by all instructions, procedures and rules of this RFQ. The Government is not obligated to determine a competitive range, conduct discussions, solicit final revised quotations, or use other techniques associated with FAR part [15](https://www.acquisition.gov/far/html/Subpart%2015_1.html#wp1095839).

The final award for this requirement will be based on best-value principles, utilizing the trade-off process. The Government is more concerned with obtaining superior technical capabilities than with making awards at the lowest overall price to the Government. Offerors are advised that the technical evaluation factors combined are significantly more important than price. Note that as submissions become more technically equal in their merit, the total evaluated price becomes more important.

5.0 Evaluation Process
======================

The Government intends to utilize a phased approach for this procurement as described below. To be considered for award, offerors must successfully pass through each phase.

1.  Phase 1: Technical Evaluation - The Government will evaluate the offeror’s performance or capability acceptability based on the following non-price technical factor: Technical Understanding and Approach.

2.  Phase 2: Pricing Schedule - Offeror’s Price as provided in the price quotation received via the Google Form will be reviewed separately from the technical evaluation.

The evaluation factors for award are as follows in descending order of importance:

-   Factor 1: Technical Understanding and Approach

-   Factor 2: Price

For this solicitation, technical factors are more important than price.

5.1 Phase 1 Technical Evaluation
--------------------------------

### Technical Understanding and Approach

The offeror shall describe within the [Technical Evaluation Google Form](https://goo.gl/forms/74p2CyXLSsVETrzm1), level of knowledge, technical expertise and overall understanding of the requirements. The government will evaluate the following:

-   Level of knowledge, technical expertise, and overall understanding of the requirements to manage an incident management response platform for large and high-profile projects, showing the ability to satisfy the needs outlined in Section 2.0.

-   Maintaining a reliable, secure incident management response platform with constant updates to address new and known vulnerabilities so that the needs outlined in section 2.0 and requirements outlined in section 3.0 can be satisfied throughout the period of performance.

-   Stated approach outlining how the offeror will satisfy each of the requirements in Sections 3.1, 3.2, and 3.3.

5.2 Phase 2 Price Evaluation
----------------------------

Prices shall be submitted via the [Price Evaluation Form](https://goo.gl/forms/SakMJFEEjesOE6k93). Proposed prices shall be evaluated for reasonableness and consistency with industry standards.

Evaluation of options under FAR [52.217-8](https://www.acquisition.gov/far/html/52_217_221.html#wp1135887) will be accomplished by using the prices offered for the last option period to determine the price for a 6-month option period, which will be added to the base and other option years to arrive at the total price. Evaluation of options will not obligate the Government to exercise the option(s).

The Government also reserves the right to make no award.

6.0 Period of Performance
=========================

The period of performance for this order is a base period of twelve months with four option periods of twelve months each. The period of performance may be bilaterally modified in order to complete the requirements outlined in the SOW.

7.0 Type of Contract
====================

Offerors must provide a Firm-Fixed-Price (FFP) quote for the services described in Section 3.0. The quote must outline the annual license pricing per license.

8.0 Invoicing
=============

The selected vendor must submit invoices on a monthly basis. The selected vendor must submit a final invoice at the end of the period of performance within 60 calendar days from contract completion. No further charges are to be billed following the final invoice submission. With the submission of a final invoice, a completed and signed Release of Claims (GSA Form 1142) shall be provided to the CO.

8.1 Content of Invoice
----------------------

The selected vendor will be provided with the following information when the acquisition has been awarded:

-   Contract/Order Number

-   Period of performance covered by the invoice

-   CLIN number and title

-   The Accounting Number Associated with the task order

All of this information must be included on each invoice in addition to the requirements for a proper invoice specified in FAR 52.212-4 (g) and the Prompt Payment clause, FAR 52.212-4(i)(2).

8.2 Invoice Submission
----------------------

The selected vendor is required to submit invoices to GSA Vendor Customer Self Service (VCSS) and the Contracting Officer Representative (COR). All invoicing questions can be directed to customer support at 866-450-6588 or the VCSS customer service site [https://vcss.ocfo.gsa.gov/](https://vcss.ocfo.gsa.gov/). GSA TTS is unable to address any questions related to the invoicing system.

**8.3 Payment Terms**

SaaS is billed in arrears in accordance with 31 U.S.C. 3324. The selected vendor may invoice as frequently as monthly, in arrears, for the value of the service provided in the preceding month. Each monthly invoice equals 1/12th of the total annual price. Vendors may invoice less frequently, for example, quarterly, or annually, but may only bill in arrears for services provided up to the point of the invoice. Payment will not be made in advance of services.

8.4 Nonconforming Products and Services
---------------------------------------

Non-conforming services will be rejected. If the deficiencies cannot be corrected within ten (10) work days, the vendor will immediately notify the TTS COR of the reason for the delay and provide a proposed corrective action plan within five (5) work days.

9.0 Administration
==================

This acquisition will be administered by the following individuals, who will also monitor the selected vendor’s performance:

1.  GSA Technical Point of Contact: Erik Burgess

2.  GSA TTS Contracting Officer: Michelle McNellis

3.  GSA TTS Contracting Officer Representative: Erik Burgess

10.0 TTS Transparency Policy
============================

Vendors are advised that TTS reserves the right to publish documents associated with this acquisition on a publicly-available website, including any Requests for Quotation or their amendments, as well as question and answer exchanges with vendors without source-identifying information removed. TTS reserves the right to publish any other relevant information that is not confidential or proprietary in nature, but will not publish any source selection sensitive information that would otherwise implicate procurement integrity concerns.

Upon award of the acquisition, TTS may publish the total price of the selected proposal and certain non-source-identifying data (e.g. the number of bids, the mean price, the median, and the standard deviation of price). During the performance of this task order, TTS may similarly publish data related to project management (e.g. user stories, milestones, and performance metrics) and top-line spending data.

11.0 Clauses
============

See Addendum - Commercial Contract Clauses
