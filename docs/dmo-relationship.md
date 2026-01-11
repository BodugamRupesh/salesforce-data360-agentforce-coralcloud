# 03 — ExternalReservation Relationship Verification

## Goal
Ensure ExternalReservation DMO is related to Individual so reservations can link to unified profiles.

## Steps Performed
1. Data Model tab → ExternalReservation
2. Relationships tab checked
3. Verified relationship:
   - Field: Contact ID
   - Cardinality: N:1
   - Related Object: Individual
   - Related Field: Individual Id
4. Activated relationship if inactive

## Screenshot Proof
- images/externalreservation-relationship.png

