### **Internal Strategy Memo: kimi Proposal**

**Prepared By:** Praveen,Manager
**Date:** 2025-06-20
**Subject:** Strategy & Key Terms for the kimi Functional Safety SOW

---

#### **1. Opportunity Overview**

We have a strong opportunity with kimi for their inverter firmware project. They are facing challenges on two fronts:
1.  **Scope Creep & V&V Burden:** They need to complete ~110 safety requirements and perform all the rigorous ISO 26262 V&V, which is tying up their core team.
2.  **Critical Bottleneck:** Their DYNO test environment is failing due to CAN DBC file issues, blocking their testing progress.

This is a perfect fit for our blended-shore model. We can propose our India Design Center for the bulk of the V&V work and use our US-based consultant for high-value functional safety guidance.

---

#### **2. Proposed Solution & SOW Strategy**

The client's scope isn't fully defined, especially the "code refactoring" and the root cause of the DBC issue. A fixed-price bid is too risky. We must structure the SOW to protect us from these unknowns.

*   **The 3-Phase Approach:** I will propose a three-phase project structure.
    *   **Phase 1 - "Paid Discovery":** This is our key de-risking element. We'll frame it as a "Discovery" or "Gap Analysis" phase. During this phase, we will get paid (on a T&M basis) to analyze their code, define the *actual* scope of work, and deliver the initial DBC fix as a quick win.
    *   **Phases 2 & 3 - "Indicative Implementation":** The SOW must state that the plans for these later phases are **indicative only** and will be formally defined by the output of Phase 1. This gives us a natural point to draft a Change Order if the scope is larger than we currently estimate.

---

#### **3. Critical Commercial Terms to Include in the SOW**

This section is non-negotiable. These points must be clearly articulated in the final SOW document.

*   **Pricing Model: T&M Only.** We will not offer a fixed-price option. Frame this as providing the flexibility they need for a project with evolving requirements.
*   **Pass-Through Tool Costs:** The SOW must have a separate section for "Additional Pricing." We will explicitly state that licenses for tools like **Vector Cast** and **PC-LINT** are the client's financial responsibility. We can offer to purchase them on their behalf, but the cost will be passed through on the invoice.
*   **The 15-Day Acceptance Clause:** To prevent our deliverables from getting stuck in review limbo, I will introduce a "deemed acceptance" clause. Proposing **15 calendar days** is reasonable. If they don't provide feedback within that window, the deliverable is considered accepted. This is critical for maintaining project velocity and protecting our margins.
*   **Budget Cap & Change Management:** We'll include an estimated project cost for their budgeting purposes, but clearly state it's an estimate. The SOW must specify that we will trigger a **Change Order process at 80%** of the budget burn. This formalizes the process for budget extensions and prevents us from working for free.

---

#### **4. Defining Client Responsibilities (Our Protection)**

We need to clearly list all dependencies on kimi. This shifts the onus of delays onto them and protects us if the project stalls due to their inaction.

The "Client Responsibilities" section of the SOW must require them to provide:
*   **Hardware:** Two complete hardware kits with harnesses, shipped to our India center at their expense.
*   **Remote Access:** Uninterrupted access to a stable, pre-configured HIL system.
*   **A Configured Laptop:** We don't want to waste billable hours setting up a development environment. They need to provide a laptop that is ready to go.
*   **Timely Access to SMEs:** Their experts must be available for clarifications.

### 5. Contact Information

Please direct all questions to:
[praveen/Hyderabad, e.g., Technical Manager ]
[pravenn@cfeynman.com]
[+1 9234567892]

