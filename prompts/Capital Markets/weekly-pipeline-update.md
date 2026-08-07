# Prompt Template: Weekly Deal Pipeline Update

**Business Unit:** Capital Markets — Internal Process / Team Efficiency

## Purpose
Speed up the weekly internal pipeline reporting process. Brokers/analysts fill in raw deal status notes and get back a clean, standardized pipeline update ready to send to the Market Leader or paste into the CRM/pipeline tracker — instead of manually reformatting the same report every week.

## Fields to fill out before use
- **Broker/Team Name:** [Name(s)]
- **Reporting Week Ending:** [Date]
- **Market Leader / Recipient:** [Name]
- **Active Listings (raw notes):** [Property name, status, next step, target close/list date — one line per deal]
- **New Business Won This Week:** [Property name, client, fee estimate]
- **Deals Lost / Dropped This Week:** [Property name, reason]
- **Deals Under LOI / Contract:** [Property name, stage, expected close date, key holdup if any]
- **Prospecting / Pitch Activity:** [# of pitches this week, notable ones]
- **Blockers Needing Manager Attention:** [Raw notes on anything stuck]

## Prompt

You are a Capital Markets broker's assistant helping prepare the weekly pipeline update for internal reporting. Take the raw, informal notes below and convert them into a clean, standardized pipeline report with these sections, in this order: (1) Summary line — total active pipeline count and $ volume if inferable, (2) New Business Won, (3) Deals Under LOI/Contract, (4) Active Listings, (5) Deals Lost/Dropped, (6) Prospecting Activity, (7) Blockers/Needs Manager Attention. Use terse, scannable bullet points — one line per deal, no filler language. Preserve every deal mentioned in the raw notes; do not invent or drop any.

Broker/Team: {Broker/Team Name}
Week Ending: {Reporting Week Ending}
Recipient: {Market Leader / Recipient}
Active Listings (raw): {Active Listings (raw notes)}
New Business Won (raw): {New Business Won This Week}
Lost/Dropped (raw): {Deals Lost / Dropped This Week}
Under LOI/Contract (raw): {Deals Under LOI / Contract}
Prospecting Activity (raw): {Prospecting / Pitch Activity}
Blockers (raw): {Blockers Needing Manager Attention}

Output as a formatted email body ready to send to {Market Leader / Recipient}, with a subject line suggestion at the top.
