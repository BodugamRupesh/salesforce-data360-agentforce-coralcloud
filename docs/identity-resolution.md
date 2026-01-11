# 02 — Identity Resolution Setup (Unified Profiles)

## Goal
Match external guest identities with Salesforce Contacts and generate unified profiles.

## Ruleset Configuration
- Data Space: Default
- Primary DMO: Individual
- Ruleset ID: ccid
- Ruleset Name: Guest Name and Email
- Run jobs automatically: OFF

## Match Rules Used
- Fuzzy Name
- Normalized Email

## Steps Performed
1. Identity Resolutions → New
2. Create new ruleset
3. Configure Match Rules
4. Save and Run Ruleset
5. Verified Last Job Status = Succeeded
6. Confirmed Total Unified Profiles had values

## Screenshot Proof
- images/identity-ruleset-succeeded.png

