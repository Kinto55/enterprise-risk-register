# GRC Architecture: Enterprise Risk & Controls Management

## Project Overview
A risk register with no issue tracking or SLA enforcement is just administrative noise. This project bridges the gap between theoretical compliance and production reality. I built an end-to-end Risk and Controls Management Architecture for "Lemonav," a simulated B2B SaaS company [1]. This project demonstrates how to transition from simply identifying raw technical vulnerabilities to actively auditing control failures and governing enterprise risk.

## Core Components
This repository contains the three main pillars of a functional GRC architecture:
1. **Quantitative Risk Register:** A comprehensive risk matrix scoring 11 critical SaaS vulnerabilities using a 1-25 Impact x Likelihood methodology [2-4].
2. **Control Effectiveness Issue Tracker:** An audit of 20 simulated operational issues, identifying where technical controls (like MFA and RBAC) failed in the real world, causing residual risk scores to increase [5-7].

3. **Executive Risk Dashboard:** A visual translation of raw risk data into a Risk Heatmap and Dashboard designed for C-suite visibility and strategic decision-making [8, 9].

## Key Highlights
* **Dynamic Risk Scoring:** Rather than accepting "paper compliance," I adjusted Residual Risk scores based on actual control performance (e.g., escalating Risk-001 from 20 to a critical 25 due to active MFA bypasses) [10, 11].
* **Strict SLA Enforcement:** Tied critical vulnerabilities directly to a maximum 15-day remediation window (with a 7-day target) to enforce accountability [11, 12]. 
* **Cross-Functional Ownership:** Mapped each risk to specific departmental owners (Engineering, IT, HR, Marketing, etc.) to ensure remediation tasks had clear business owners [12-14].

## Tools & Frameworks
`Governance, Risk, & Compliance (GRC)` | `IT Audit` | `NIST` | `Quantitative Risk Scoring` | `SLA Enforcement`
