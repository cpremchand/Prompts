# Request for Proposal (RFP)

**Title:** Functional Safety Software Development and CAN Database Optimization for Inverter Module

**Issue Date:** July 10, 2025

**Issued By:** Danfoss

---

### 1. Introduction & Executive Summary

Danfoss is a global leader in engineering solutions. We are currently in the development phase of advanced firmware for a new inverter module. To ensure the highest standards of safety and reliability, this project requires strict adherence to functional safety standards and a robust testing framework.

Danfoss is seeking proposals from qualified engineering service providers to support our team in two key areas:
1.  The implementation, verification, and validation (V&V) of safety-critical software, compliant with the ISO 26262 standard.
2.  The optimization of our CAN database (DBC) files to resolve data acquisition issues within our DYNO test environment.

We are looking for a partner with proven expertise in embedded systems, functional safety (specifically ISO 26262), and automotive testing environments to act as an extension of our internal team.

### 2. Project Background

The project focuses on the firmware for a safety-critical inverter module. A significant portion of the software development for the safety-rated CPU is underway, but requires completion and rigorous validation. Concurrently, our hardware-in-the-loop (HIL) and DYNO testing environments are experiencing data acquisition challenges that have been traced back to inconsistencies in our CAN database translation files.

This RFP seeks a vendor to provide the necessary services to complete the software development lifecycle for the safety functions and to rectify the data acquisition pipeline.

### 3. Scope of Work

The selected vendor will be responsible for the following tasks, divided into two primary workstreams:

**Workstream 1: Functional Safety Software � Implementation, Refactoring, and V&V**

The primary objective is to finalize the software for the Safety CPU in accordance with the **ISO 26262-6** standard.

*   **Requirement Implementation:** Implement approximately 110 remaining safety software requirements.
*   **Code Refactoring:** Refactor the existing codebase to align with Danfoss�s specified TSC (Technical Safety Concept) Architecture.
*   **Design Documentation:** Create comprehensive architectural and detailed design documents that serve as evidence for the safety lifecycle and design choices.
*   **Unit Testing:** Develop and execute unit tests to achieve the required code coverage metrics (Statement, Branch, MC/DC) as stipulated by the safety plan.
*   **Bench-Level Testing:** Perform integration and requirement-based testing on a physical bench setup.
*   **HIL Testing:** Conduct remote testing on Danfoss�s HIL setup, including the execution of fault insertion tests to validate safety mechanism effectiveness.

**Workstream 2: DYNO CAN Issues � DBC Update and Optimization**

The objective is to resolve a critical data acquisition bottleneck on our DYNO test bench.

*   **Problem Analysis:** Investigate the root cause of the data acquisition failure related to CAN translation.
*   **DBC File Consolidation:** Merge, update, and rationalize multiple existing DBC files into one or more master DBCs that are fully compatible with the data acquisition module used by the DYNO.

### 4. Expected Deliverables

The vendor is expected to produce the following key deliverables:

1.  **Consolidated DBC File(s):** A fully functional and optimized set of DBC files for the DYNO data acquisition system.
2.  **Software Design Document:** A comprehensive document detailing the high-level and low-level design of the safety software.
3.  **Refactored Safety Software:** The complete, reviewed, and tested source code for the implemented safety functions.
4.  **Software Verification & Validation Report:** A detailed report containing the results and evidence from:
    *   Static Code Analysis (e.g., MISRA compliance).
    *   Unit Test results and code coverage metrics.
    *   Integration and Requirement-Based Test (RBT) results.
    *   HIL testing results, including fault insertion validation.

### 5. Vendor Qualifications & Requirements

Proposers should demonstrate the following qualifications:

*   Extensive experience in embedded software development for automotive or industrial applications.
*   Deep, demonstrable expertise in the **ISO 26262** functional safety standard, particularly Part 6 (Software).
*   Proven track record of software verification and validation, including unit testing, integration testing, and HIL testing.
*   Experience with automotive communication protocols, especially CAN, and hands-on experience with DBC file creation and management.
*   Familiarity with common automotive development and testing tools (e.g., Vector CANoe/CANalyzer, VectorCAST, PC-LINT, HIL systems).
*   Experience working in a collaborative, extended-team model.

### 6. Proposal Submission Guidelines

Interested vendors should structure their proposals to include the following:

1.  **Company Overview:** A brief introduction to your company, its core competencies, and relevant experience.
2.  **Technical Approach:** A detailed description of your proposed methodology for tackling both workstreams. This should include your understanding of the challenges and your plan for each phase (e.g., discovery, implementation, V&V).
3.  **Project Plan & Timeline:** A high-level project plan with estimated timelines for major milestones and deliverables.
4.  **Team Structure:** The proposed roles, responsibilities, and experience of the team members who will be assigned to this project. Please specify their location (e.g., onshore/offshore).
5.  **Pricing Model:** A detailed breakdown of your proposed pricing. Please specify if this is Time & Materials (T&M), Fixed Price, or another model. Include hourly rates for all proposed roles.
6.  **Assumptions & Dependencies:** A list of any assumptions made in your proposal and any dependencies on Danfoss (e.g., hardware availability, access to systems, etc.).

### 7. RFP Timeline

*   **RFP Issue Date:** July 10, 2025
*   **Deadline for Questions:** July 24, 2025
*   **Proposal Submission Deadline:** August 7, 2025
*   **Vendor Selection:** August 21, 2025
*   **Project Kick-off (Target):** September 4, 2025

### 8. Contact Information

Please direct all questions and submit final proposals to:

[peter parker/New york, e.g., Head of Procurement]
[spiderman@danfoss.com]
[+1 9234567892]
