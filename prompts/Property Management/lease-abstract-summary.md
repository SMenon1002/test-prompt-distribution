# Prompt Template: Lease Abstract Summary

**Business Unit:** Property Management (Asset & Property Services)

## Purpose
Convert key lease terms into a standardized lease abstract for property management and accounting teams.

## Fields to fill out before use
- **Property Name / Address:** [Building name, address]
- **Tenant Legal Name:** [Entity name]
- **Suite / Unit Number:** [e.g., Suite 400]
- **Rentable Square Footage:** [SF]
- **Lease Commencement Date:** [Date]
- **Lease Expiration Date:** [Date]
- **Renewal Options:** [# of options, term length, notice period]
- **Base Rent Schedule:** [Rate per SF or flat amount, escalation schedule/dates]
- **Free Rent / Abatement Period:** [Duration and terms]
- **Operating Expense Structure:** [NNN / Gross / Modified Gross — reimbursement method]
- **Security Deposit / LOC Amount:** [$ amount]
- **Tenant Improvement Allowance:** [$ amount, $/SF]
- **Permitted Use:** [Clause description]
- **Exclusive Use / Co-Tenancy Clauses:** [If applicable]
- **Assignment / Sublease Rights:** [Summary of clause]
- **Early Termination Rights:** [Terms, fees, notice period]
- **Landlord/Tenant Notice Addresses:** [Contact info]

## Prompt

You are a CBRE Property Management analyst creating a standardized lease abstract for internal use by the accounting and asset management teams. Using the lease terms below, produce a structured lease abstract with clearly labeled fields matching CBRE's standard abstract format. Flag any unusual or non-standard clauses (e.g., unusual co-tenancy, early termination, or exclusive use provisions) in a separate "Key Risks / Non-Standard Terms" section at the end.

Property: {Property Name / Address}
Tenant: {Tenant Legal Name}
Suite: {Suite / Unit Number}
RSF: {Rentable Square Footage}
Commencement Date: {Lease Commencement Date}
Expiration Date: {Lease Expiration Date}
Renewal Options: {Renewal Options}
Base Rent Schedule: {Base Rent Schedule}
Free Rent/Abatement: {Free Rent / Abatement Period}
OpEx Structure: {Operating Expense Structure}
Security Deposit: {Security Deposit / LOC Amount}
TI Allowance: {Tenant Improvement Allowance}
Permitted Use: {Permitted Use}
Exclusive/Co-Tenancy: {Exclusive Use / Co-Tenancy Clauses}
Assignment/Sublease: {Assignment / Sublease Rights}
Early Termination: {Early Termination Rights}
Notice Addresses: {Landlord/Tenant Notice Addresses}

Output as a structured table followed by the "Key Risks / Non-Standard Terms" bullet list.
