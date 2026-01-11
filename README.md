# Salesforce Data 360 + Agentforce Project (Coral Cloud Resort)

This repository documents my hands-on Salesforce implementation project based on the Coral Cloud Resorts Trailhead scenario. The project combines **Salesforce Data 360 (Data Cloud)** and **Agentforce** to streamline guest check-in by bringing external reservation data into Salesforce Contacts.

---

## 🚀 Objective
Enable a unified guest experience by:
- Ingesting external reservation/guest data into Data 360
- Matching external guest identities with internal Salesforce Contacts
- Displaying external reservations directly on the Contact page
- Extending Agentforce using a Flow-based action (AI + automation)

---

## ✅ Key Work Completed
### Data 360 (Data Cloud)
- Enabled and deployed **Data Streams** from `AIPlusData Custom Data Bundle`
- Verified ingestion success with non-zero record counts
- Created **Identity Resolution Ruleset**
  - Ruleset ID: `ccid`
  - Match Rules: **Fuzzy Name + Normalized Email**
  - Successfully unified profiles

### CRM Enrichment (Contact Page)
- Verified/Activated DMO relationship: **ExternalReservation → Individual**
- Created **Data Cloud Related List** for `ExternalReservation`
  - Label: `Reservations`
- Updated Contact Lightning Record Page
  - Added **Dynamic Related List - Single**
  - Display fields: Check-in Date, Check-out Date, Room Type, Reservation Status
  - Added filter: `Check-in Date != blank`

### Agentforce Extension
- Designed a Flow-based action to extend Agentforce using reservation data (Unit 3)

---

## 📸 Screenshots
See `/images` folder for implementation proof.

---

## 🧰 Tools Used
- Salesforce Data 360 (Data Cloud)
- Data Streams, Data Model Objects, DMO relationships
- Identity Resolution (Unified Profiles)
- Lightning App Builder (Dynamic Related List)
- Agentforce + Salesforce Flow

---

## 👤 Author
**Rupesh Reddy**  
GitHub: (your github profile link)  
LinkedIn: (your linkedin profile link)
