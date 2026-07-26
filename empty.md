Final Project: Testing and Release Planning Kit
Estimated time: 60 minutes

This final project serves as your opportunity to demonstrate everything you've learned in this course by creating a complete Testing and Release Planning Kit. Your role is to simulate real-world responsibilities as a systems professional for NexaCare Solutions, overseeing the preparation, rollout, and monitoring of a major software release.

You will structure your deliverables into eight clearly defined sections. A pre-formatted Word template has been provided. Simply copy and paste your responses under each section title in the template, and submit the completed document in the next step.

Submission instructions
A pre-formatted template has been provided to help you organize your responses efficiently. Download the template by right-clicking the link and opening it in a new tab.

Project template:

Word template
PDF template
Non Functional Requirements Kit
All eight sections are already included with appropriate headings. Simply copy and paste your content below each section title as instructed above.

When you are finished, submit the document in the next step.

Evaluation and submission guidelines
This reading outlines the expectations, content requirements, and evaluation criteria for each of the eight components of your final project. Use these guidelines to structure your responses clearly and professionally. Your work will be assessed based on completeness, clarity, relevance to the scenario, and the application of course concepts.

A recap of the scenario and project requirements is provided to help you understand the project better.

The scenario
You are working as a systems professional at NexaCare Solutions, a health technology company focused on improving patient engagement and clinic operations through digital platforms.

NexaCare is preparing to launch a major upgrade to its existing web-based appointment scheduling platform. This platform is used by thousands of patients to book, manage, and track healthcare appointments across a wide network of clinics and practitioners.

The upcoming software release introduces critical new features designed to enhance both usability and operational efficiency. The business goal is to improve appointment reliability, reduce patient no-shows, and provide a more modern, integrated user experience.

What's included in the upgrade?
The following features are being introduced in the new version of the platform:

SMS reminders: Patients will receive automated text message reminders for upcoming appointments, reducing missed appointments and increasing patient engagement.

Real-time doctor availability: Patients can view and book appointments based on live availability data from healthcare providers.

Calendar integration: Patients will be able to sync their appointments with Google Calendar and Microsoft Outlook, making it easier to manage their healthcare alongside their daily schedule.

Redesigned user interface: The platform's interface has been completely overhauled to improve usability, reduce friction during booking, and ensure accessibility for users of all ages and digital literacy levels.

Project scenario: Version 3.0 release planning
You are a systems professional at NexaCare Solutions, a mid-sized health technology company that specializes in digital tools for medical clinics and private practices. NexaCare's flagship product is a web-based appointment scheduling platform, which is currently in use by over 300 clinics across North America.

Version 3.0 highlights
The company is preparing to launch version 3.0 of the platform, delivering several highly requested features aimed at improving both patient satisfaction and clinic efficiency:

SMS reminders
Patients receive automated text messages 24 hours and 1 hour before their appointments.
Built using a new third-party SMS service not previously integrated.
Real-time doctor availability
Clinics can instantly update availability.
Reduces booking delays, no-shows, and double-bookings.
Calendar integration
Enables syncing with Google Calendar and Outlook.
Available for both patients and providers.
Redesigned user interface
Improved accessibility, responsiveness, and usability across desktop and mobile platforms.
Modern, clean design aligned with WCAG accessibility standards.
Risk considerations
Leadership is proceeding cautiously due to a recent data loss incident from a failed upgrade in another product line. Your coordination and execution plan must be:

Thorough
Well-documented
Risk-aware
Compliance-focused
Additional context
Consider the following elements while planning and coordinating the release:

Diverse client base

Some clinics use only basic scheduling tools.
Others have deep API integrations with their own patient management systems.
New SMS infrastructure

First-time integration of the third-party SMS platform.
Requires extra QA and fallback planning.
Pilot program

A group of 20 clinics will receive the update first.
Feedback and telemetry will inform the broader rollout.
Sensitive data involved

Over 1.2 million patient records, including health and contact data.
Compliance with HIPAA and other privacy regulations is mandatory.
Approved downtime window

Maintenance must occur on Saturday from 12:00 AM to 6:00 AM EST.
Downtime must be minimized or avoided if possible.
Performance requirements

Current system handles an average of 500 concurrent users during normal hours
Peak traffic (Monday mornings 8–10 AM) reaches 1500–2500 concurrent users
Clinics report that appointment booking must be completed within 3 seconds to maintain workflow efficiency
SMS delivery must occur within 2 minutes of the scheduled send time
Real-time availability updates must reflect across all user sessions within 5 seconds
Internal teams to coordinate with
You are expected to work closely with the following internal stakeholders:

QA team: For test coverage, regression testing, and pilot support
DevOps: For deployment orchestration, rollback plans, and monitoring setup
Product management: For feature readiness, communications, and roadmap alignment
Support team: For client-facing materials, issue tracking, and escalation handling
Your primary objective
Ensure a safe, compliant, and successful rollout of version 3.0 that minimizes disruption, upholds data integrity, maintains performance standards, and maximizes stakeholder confidence.
1. Test strategy outline
What to include:

A clear description of your overall approach to testing the upgraded platform

Types of testing you plan to perform (e.g., unit, functional, integration, regression, performance, user acceptance testing)

Justification for why each type of testing is included

Test priorities: Which features or components are most critical?

Testing objectives: What should testing achieve? (e.g., stability, usability, compliance)

Any testing tools or frameworks to be used (if applicable)

Evaluation focus:

Clarity, completeness, relevance to the NexaCare platform, and strategic alignment with business goals.

2. Traceability matrix
What to include:

A tabular matrix mapping each requirement or use case to specific test cases

Unique identifiers for each requirement and test case (e.g., REQ-01, TC-01)

A column indicating test coverage status (e.g., covered, not covered, partial)

Optionally, add priorities or risk levels for each requirement

Evaluation focus:

Accuracy of mapping, thoroughness in coverage, and ability to trace tests to business needs.

3. Annotated test plans
What to include:

Detailed test plans for at least 2–3 major features (e.g., SMS reminders, calendar integration)

Test objectives, preconditions, test steps, expected results, and actual results

Annotations to highlight potential risks, edge cases, or special considerations

Clear organization with headings or bullet points for readability

Evaluation focus:

Coverage of critical features, attention to detail, and ability to identify testing risks.

4. Deployment checklist
What to include:

A sequential checklist of deployment tasks

Roles and responsibilities (who does what)

Estimated timelines or time windows for each task

Go/no-go criteria that determine whether to proceed with launch

Pre-deployment and post-deployment tasks

Evaluation focus:

Practicality, organization, clarity of steps, and inclusion of realistic checks and controls.

5. Rollback strategy
What to include:

Conditions that would trigger a rollback (e.g., critical bugs, system failure)

Step-by-step rollback procedures

Who is responsible for initiating and managing the rollback

Communication plan if rollback is executed

Timeframe for rollback and recovery

Evaluation focus:

Feasibility, clarity, and risk awareness in managing post-release failures.

6. Data migration plan
What to include:

Source and destination systems involved

Data mapping rules (e.g., field-to-field transformations)

Record counts to be migrated

Validation and verification steps (before and after migration)

Handling of errors, duplicates, or exceptions

Evaluation focus:

Technical accuracy, completeness of process, and understanding of data integrity concerns.

7. Post-deployment monitoring summary
What to include:

Metrics to be monitored (e.g., uptime, error rates, API response time, user logins)

Tools or dashboards used for monitoring

Frequency of checks and reporting process

Who will receive monitoring reports

Plan for responding to issues detected during monitoring

Evaluation focus:

Relevance of metrics, clarity of monitoring plan, and responsiveness to potential issues.

8. Non-functional requirements and performance plan
What to include:

This section integrates your knowledge of performance optimization and monitoring strategies. You must address the following components:

A. Non-functional requirements (NFRs) definition
Define specific, measurable NFRs for the NexaCare platform across these categories:

Performance: Response time targets for key operations (e.g., appointment booking, search, calendar sync)
Scalability: Concurrent user capacity for normal and peak traffic scenarios
Reliability: System uptime targets and maximum acceptable downtime
Availability: Service availability percentage (e.g., 99.5%, 99.9%)
Latency: Maximum acceptable latency for critical operations (SMS delivery, availability updates)
Example format:

NFR category	Specific requirement	Target value	Measurement method
Performance	Appointment booking completion time	<3 seconds	API response time monitoring
Scalability	Peak concurrent users	2500 users	Load testing validation
B. Golden signals monitoring plan
Identify the Four Golden Signals for the NexaCare platform and define how you will monitor them:

Golden signal	Metric name	How to measure	Target/Threshold	Business impact
Latency	API response time P95	Application performance monitoring	<500 ms	Slow responses cause booking abandonment
Traffic	Active concurrent users	Real-time user sessions	Monitor for >2500	Capacity planning and scaling triggers
Errors	HTTP 5xx error rate	Error tracking system	<0.5%	Failed bookings = lost appointments
Saturation	Database connection pool utilization	Database monitoring	<80%	Connection exhaustion causes failures
C. Peak traffic preparation
Address the Monday morning peak traffic scenario (3–5x normal traffic):

Which metrics need adjusted thresholds during peak periods?
What infrastructure adjustments are needed?
How will you monitor for performance degradation?
What's your plan if performance drops below acceptable levels?
Example:

Metric	Normal threshold	Peak period threshold	Reasoning
Database CPU	>85% alert	>95% alert	Higher utilization expected during peak
API response time	>2s alert	>4s alert	Accept slightly degraded performance vs. false alarms
Evaluation focus:

Completeness of NFR definitions with specific, measurable targets
Understanding of the Four Golden Signals and their application to healthcare scheduling
Practical, prioritized optimization strategies across all three performance layers
Appropriate SLOs and alert thresholds that balance business needs with technical constraints
Realistic approach to handling variable traffic patterns
Evidence of 80/20 rule application in prioritization decisions
Project evaluation criteria
This final project comprises 40 points. Each component is evaluated based on the following criteria:

Component	Marks	Evaluation criteria
Test strategy outline	5	Clarity, completeness, and alignment with project goals
Traceability matrix	5	Accuracy and detail in mapping requirements to test cases
Annotated test plans	5	Coverage of key features, identification of risks, and clarity
Deployment checklist	5	Practicality, completeness, and clarity of execution steps
Rollback strategy	5	Clear, actionable plan for handling critical failures
Data migration plan	5	Realistic approach to data transfer and validation
Post-deployment monitoring summary	5	Relevance, clarity, and feasibility of monitoring strategy
Non-functional requirements and performance plan	5	Comprehensive NFR definition, appropriate performance targets, practical optimization strategies, and understanding of monitoring principles
Working guidelines
To ensure a smooth working experience, please follow these best practices:

Save your work regularly. Use versioning (e.g., v1, v2) to track changes.

Work offline or in a cloud-based editor (e.g., Microsoft Word Online or Google Docs) to prevent data loss.

Back up your file to a secure location such as OneDrive, Google Drive, or a USB device.

Use clear, concise, and professional language.

Review the NexaCare scenario and use cases carefully to keep your responses relevant and focused.

Proofread your document before submitting to ensure it is free from spelling, grammar, and formatting errors.

Apply course concepts from all modules, including the performance optimization and monitoring strategies you learned in the labs.