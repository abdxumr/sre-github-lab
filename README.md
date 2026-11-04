# sre-github-lab

Requirement Documentation for Student Task Tracker

\#Food Authority Management System



\##Overview



Food authorities inspect restaurants, bakeries, hotels, food factories and shops to make sure they follow food safety and hygiene standards. Today, much of this work is recorded manually, so inspectors struggle to find earlier inspection records, inspections are hard to schedule, citizen complaints are not tracked properly, and businesses with repeated violations are hard to identify.



The Food Authority Management System is a proposed web and mobile application that gives the authority one central place to register food businesses, track licenses, schedule inspections, record inspection results, manage complaints and violations, and generate reports. The intended benefit is faster inspections, better records, less paperwork, and real-time visibility of food safety compliance for management.



Target users: food authority officers, food inspectors, food business operators, citizens, and system administrators.



\##Scope

In scope: Register a food business with its owner, location, type, contact and license details.

In scope: Track licenses (active, expired, pending, renewal status) and remind businesses before expiry.

In scope: Schedule inspections, assign inspectors, and record inspection results with violations and evidence.

In scope: Let citizens submit complaints about food businesses and let the authority track their status.

In scope: Record violations, track whether they are corrected, and generate reports and dashboard statistics.

Out of scope: Physical collection and laboratory testing of food samples.

Out of scope: Manufacturing or production of food products.

Out of scope: Direct delivery of food products.

Out of scope: Automatic physical inspection of restaurants using robots.

\##Stakeholders

Food authority officers: Want to monitor food safety activities, manage businesses, licenses and complaints.

Food inspectors: Want easy access to previous inspection records and to submit inspection reports digitally.

Business operators and food manufacturers: Want to manage license, registration and inspection information and stay compliant with food regulations.

Food authority management: Wants reports and statistics on inspections, violations and compliance.

Citizens: Want to report unsafe food businesses and see that their complaints are followed up.

System administrators: Want to manage users and system settings.

Lab incharges and nutritionists: Want to update lab results and inspection-time records in the system.

Finance department: Wants to allocate funds to scheduled inspections.

\##Functional requirements

FR-01: The system shall let a food business be registered with its business name, owner name, location, type, contact information and license information.

FR-02: The system shall let a food authority officer schedule an inspection for a business and assign an inspector to it.

FR-03: The system shall let an inspector record inspection results, including hygiene conditions, violations and the overall result.

FR-04: The system shall let a citizen submit a complaint about a food business.

FR-05: The system shall notify a business before its license expires.

FR-06: The system shall display dashboard statistics for registered businesses, inspections, violations and complaints.

\##Nonfunctional requirements

NFR-01: For 1,000 stored business records, a business search shall return results within 3 seconds in at least 95 of 100 trials on the agreed test device.

NFR-02: A first-time citizen shall be able to submit a complaint in at most 5 steps, verified against the documented complaint workflow.

\##Acceptance criteria

FR-01: Given a business named "Fresh Bakery" with all required fields filled, saving the form causes "Fresh Bakery" to appear in the business list.

FR-02: After an officer assigns Inspector A to a business for a chosen date, the inspection appears in Inspector A's assigned inspections list with that date.

FR-03: After an inspector submits a result for an assigned inspection, the inspection status changes to Completed and the recorded result can be viewed.

FR-04: After a citizen submits a complaint, it appears in the authority's complaint list with the status Pending.

FR-05: For a license expiring in 30 days, the business sees an expiry reminder in its notifications.

FR-06: With two registered businesses and one recorded inspection, the dashboard shows 2 businesses and 1 inspection.

\##Assumptions and open questions

Assumption A-01: Inspectors will enter accurate inspection information, since the system cannot physically inspect a business.

Assumption A-02: Users will have internet access for the online features.

Assumption A-03: Laboratory results will be entered manually at first.

Question Q-01: How many days before expiry should the license reminder be sent?

Question Q-02: Which device and environment will test NFR-01?

Question Q-03: Which external systems (government databases, SMS and email services, online payments, map services) must be integrated in the first version?

\##Project status and viewing



Documentation only. Application implementation has not started. Clone this repository and open README.md in a Markdown viewer, or read the rendered file on GitHub.



\##Author



Abdullah Umer Farooq, BSEF24M546, Requirements Engineering semester project, PUCIT, University of the Punjab. Group members: Muhammad Qasim Mehboob (BSEF25M512) and Rehan Zafar (BSEF25M522). Replace the course text with your approved course identifier if your instructor gave one.



