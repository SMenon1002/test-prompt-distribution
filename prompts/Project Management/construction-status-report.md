# Prompt Template: Construction Project Status Report

**Business Unit:** Project Management (Turner & Townsend / CBRE PJM)

## Purpose
Generate a monthly project status report narrative for a client-facing construction/PM update.

## Fields to fill out before use
- **Project Name:** [e.g., HQ Renovation Phase 2]
- **Project Location:** [Address]
- **Client / Owner:** [Entity name]
- **Project Manager:** [Name]
- **Reporting Period:** [Month/Year]
- **Overall Project Phase:** [Design / Permitting / Construction / Closeout]
- **Percent Complete:** [%]
- **Original Budget:** [$ amount]
- **Current Forecast Cost:** [$ amount]
- **Budget Variance:** [$ amount / %]
- **Original Schedule Completion Date:** [Date]
- **Current Forecast Completion Date:** [Date]
- **Schedule Variance:** [Days ahead/behind]
- **Milestones Completed This Period:** [Bullet list]
- **Milestones Planned Next Period:** [Bullet list]
- **Open RFIs / Submittals:** [Count]
- **Change Orders (This Period):** [# and $ amount, description]
- **Safety Incidents:** [Count, description]
- **Key Risks / Issues:** [Bullet list with mitigation plans and owners]

## Prompt

You are a CBRE Project Management lead preparing the monthly status report narrative for a client construction update. Using the data below, write a concise executive summary (max 200 words) followed by sections for: Schedule Status, Budget Status, Milestones, Change Orders, Safety, and Risks/Issues. Use a factual, direct tone appropriate for owner/client stakeholders, calling out any budget or schedule variances explicitly with root cause and recovery plan.

Project Name: {Project Name}
Location: {Project Location}
Client: {Client / Owner}
Project Manager: {Project Manager}
Reporting Period: {Reporting Period}
Project Phase: {Overall Project Phase}
Percent Complete: {Percent Complete}
Original Budget: {Original Budget}
Current Forecast Cost: {Current Forecast Cost}
Budget Variance: {Budget Variance}
Original Completion Date: {Original Schedule Completion Date}
Current Forecast Completion Date: {Current Forecast Completion Date}
Schedule Variance: {Schedule Variance}
Milestones Completed: {Milestones Completed This Period}
Milestones Planned Next: {Milestones Planned Next Period}
Open RFIs/Submittals: {Open RFIs / Submittals}
Change Orders: {Change Orders (This Period)}
Safety Incidents: {Safety Incidents}
Key Risks/Issues: {Key Risks / Issues}

Output formatted for direct inclusion in a client status report PDF, with clear section headers.
