# Compound Grants Program (2024-25): Security Tooling & Enhancements

### Domain Allocator
- **Name:** Michael Lewellen
- **Email for questions:** [michael@openzeppelin.com](mailto:michael@openzeppelin.com)
- **Telegram (mutual group required):** [@cyloncat](https://t.me/cyloncat)
- **Compound Forums:** [@cyloncat on comp.xyz](https://comp.xyz/)

### Application Link
- **Apply Here:** [Questbook Compound Grants Dashboard](https://questbook.app/dashboard/?chainId=10&grantId=0x291d6eb5de3b023ce9b760ef251b303c0c0fd11a)

---

## Domain Scope & Objectives

### Key Objective
This domain seeks additional **security tooling** and **on-chain enhancements** to improve the security posture of the Compound protocol and ecosystem. Priority is given to security tools integrated into CI/CD pipelines and existing on-chain monitoring stacks.

### Requests for Proposals (RFPs)
This domain hosts the following RFPs, aligning with community priorities in dApp development:

1. **RFP1: Governance Proposal CLI**
   - Purpose: To improve security for DAO proposals submitted through Compound Governor Bravo by creating tools that allow for repeatable, automated testing of proposals.
   - Requirements: The tool should include full simulations and checks for risky actions (e.g., fund transfers, upgrades, cross-chain interactions) and must be user-friendly for non-developers.
   - Context: This would be a continuation of the Governance CLI created in the prior Proposal Safety Checks grant.

2. **RFP2: Emergency Upgrade Rollbacks for the Timelock**
   - Purpose: To develop a rollback mechanism for time-locked DAO proposals that encounter immediate issues, allowing for swift reversion to previous states by the Pause Guardian.
   - Requirements: This solution requires both an on-chain protocol change and thorough research to ensure it operates safely with Compound's upgradeable contracts.

3. **RFP3: Asset Collateral Safety Checks**
   - Purpose: To automate the process of ensuring that new collateral assets listed on Compound do not have technical integration issues.
   - Requirements: Integration checks, especially for upgradable tokens or bridge-dependent assets, should be automated.

### Additional Areas of Interest
Beyond specific RFPs, this domain is open to community-submitted ideas that improve the security of the Compound protocol, such as:
- CI/CD tooling to enhance protocol contribution security
- Improvements to security features like the Pause Guardian, Timelock, or other controls
- Solutions for unaddressed issues from previous security audits
- Educational resources on security best practices for Compound

---

## Milestone Articulation

Grants are disbursed in **COMP** (Compound's governance token) and follow a milestone-based payout system:
- Proposals should include 3-5 measurable milestones aligned with quantifiable KPIs.
- Milestones may include both **on-chain metrics** and **off-chain metrics** (e.g., traffic to the project site).
- It is recommended that one of the final milestones includes a mechanism for community feedback on the project to address significant concerns.

---

## Audit Requirement

Proposals that interact with the Compound protocol via smart contracts are required to undergo an **audit** with Compound’s security partner, **OpenZeppelin (OZ)**. Requirements will be determined in consultation with the domain allocator and OZ representatives. Successful audit completion, resolving any high-risk vulnerabilities, must be included as a milestone in the proposal.

---

## Proposal Evaluation Criteria

Each proposal is evaluated by the domain allocator and may be scored based on the following rubric:

1. **Team Experience** (0-5 points)
   - Assessment of the team’s past development experience and understanding of the proposal’s challenges and relevance to Compound.

2. **Novelty and Quality of the Idea** (0-5 points)
   - Evaluation of the proposal’s innovative approach and sustainability within the Compound ecosystem.

3. **Relevance to the Ecosystem** (0-5 points)
   - Alignment with domain RFPs and overall value added to the ecosystem.

4. **Completeness of the Plan** (0-5 points)
   - Adequacy of detail for assessing feasibility, plan completeness, and dissemination of results to the community.

5. **Feasibility of Goals and Timeline** (0-5 points)
   - Likelihood of achieving milestones within the timeline or within six months of the start date.

> **Note:** Proposals scoring highly in the evaluation rubric are more likely to be funded. However, there is no minimum threshold guaranteeing funding. Grant decisions consider the balance across project areas, grant sizes, and community benefits.

---

## Representative Examples from CGP 2.0

Examples of past proposal outcomes fitting this domain:
- Security Guides and Timelines
- Improved Token Technical Risk Report for New Market Proposals
- Custom SAST Pipelines
- Forta Monitoring Bots for Compound v3
