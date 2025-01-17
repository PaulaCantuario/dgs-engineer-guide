# DB1 Way

We understand that this documentation is not just a set of processes; it is a commitment to delivering quality software that continuously adds value to our clients.

Just as our software engineering is metrics-driven, our QA follows the same principle, with a data-driven approach for decision-making and continuous improvement.

---

## Core Principles

**1. We promote** a collaborative environment where team members contribute to identifying and solving quality issues. We understand that quality is not solely the QA's role but a shared responsibility among all parties involved in the development cycle. For this reason, we emphasize the importance of having a proactive and critical QA in all meetings and ceremonies that add value to client delivery.

**2. We focus** on preventing errors early in the development cycle by adopting the Shift Left approach. We believe it is more effective and less costly to prevent errors than to detect them in later stages.

**3. We analyze** each requirement carefully to ensure the application of the most suitable testing techniques, adapting our strategies to project changes and needs to deliver continuous quality:

| Test Type             | When to Apply                                                                                     |
|-----------------------|--------------------------------------------------------------------------------------------------|
| **Manual Testing**     | Small scopes, high subjectivity (e.g., user experience), or unique and non-repetitive scenarios. |
| **Automated Testing**  | Critical, repetitive, or complex flows that demand efficiency and precision.                     |
| **Regression Testing** | Automation to validate changes to existing functionalities and prevent negative impacts.         |
| **Exploratory Testing**| Detect unexpected and subjective issues, ideal for high-uncertainty scenarios.                   |
| **Integration Testing**| Ensure systems interact correctly, especially in complex dependencies.                          |
| **Acceptance Testing** | Validate acceptance criteria for delivery to the client or end user.                            |

---

## Software Quality Metrics

At DB1, we understand that software quality is not just about the absence of bugs but a set of indicators that help evaluate progress, identify areas for improvement, and ensure that deliveries add value. Below are the main metrics used to measure and monitor quality in our projects.

### What and How Do We Measure?

| Metric                     | Definition                                                                                   | Objective                                                                                  | How to Measure                                      |
|----------------------------|---------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|----------------------------------------------------|
| **Version Error Index (VEI)** | Number of bugs found by QA before delivery to the client.                                     | Maximize internal bug detection, reducing client-reported errors.                        | Total bugs found by QA during testing.             |
| **Client Error Index (CEI)** | Bugs reported by the client after delivery.                                                 | Continuously reduce, aligning client expectations and increasing trust in deliveries.     | Total bugs reported by the client post-delivery.   |
| **Total Error Index (TEI)**  | Sum of bugs found by QA (VEI) and by the client (CEI).                                      | Monitor overall bug volume and identify trends.                                           | VEI + CEI                                          |
| **Bug Severity**            | Classification of the bug’s impact.                                                         | Focus efforts on resolution according to impact.                                          | Impact identification and categorization when logging the bug. |
| **Bug Types**               | Categorization by affected system area.                                                     | Understand system critical points and prioritize improvements.                            | Analyze categories when registering and consolidating bugs.      |
| **Correction and Retest Effort** | Hours spent correcting and validating identified defects.                                   | Minimize wasted time on corrections and rework, promoting defect prevention.              | Log hours spent per delivery and consolidate monthly.           |
| **Bug Density**             | Ratio of development effort to bug correction effort.                                        | Maintain a low index, indicating an efficient development process.                        | Correction hours / Development hours.              |

---

## Test Health Assessment

We assess the maturity and health of test processes within projects monthly, identifying points of concern and improvement opportunities. As part of this assessment, we check:

- If QA performs testing activities within established standards.
- If identified errors are documented according to established standards.
- If QA actively participates in planning/refinement meetings.
- If QA conducts test automation and its level of coverage.
- If team-generated documentation and test results are available and up-to-date for all team members.
- If there is a dedicated test environment.
- If testing is compromised by delays in other development phases.

This way, in addition to monitoring the evolution of quality metrics, we ensure the health of the testing process within teams.

---

## Test Automation Guidelines

**1. We encourage** the need for automation in unit tests because they are executed frequently, are faster, and have lower maintenance costs.

**2. We prioritize** automation in integration and API tests for critical and essential flows requiring system communication.

**3. We do not exclude automation** of main flows in interface and end-to-end tests. Using the testing pyramid as a guide to avoid excessive manual testing, we balance effort and coverage in end-to-end tests.

---

## QA Responsibility and Commitment

We have the responsibility to maintain high-quality indicators and promote a culture of continuous improvement. We do this through technical review sessions (chapter reviews), where we discuss and evaluate QA best practices and share knowledge to strengthen the team as a whole.

_Maintaining poor software is costly, both in terms of time and money. The "DB1 Way of QA" aims not only to ensure quality but also to protect our clients' investment, delivering value and trust with every new software version._
