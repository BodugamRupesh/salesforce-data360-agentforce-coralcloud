# 05 — Add Reservations to Contact Lightning Page

## Goal
Show external reservation records inside Salesforce Contact page layout.

## Steps Performed
1. Setup → Lightning Record Pages
2. Contact Record Page → Edit
3. Related tab → added Dynamic Related List - Single
4. Selected Related List: Reservations
5. Added fields:
   - Check-in Date
   - Check-out Date
   - Room Type
   - Reservation Status
6. Removed Record ID field
7. Added filter:
   - Check-in Date != blank
8. Save + Activate (Org Default)

## Screenshot Proof
- images/contact-page-reservations.png

