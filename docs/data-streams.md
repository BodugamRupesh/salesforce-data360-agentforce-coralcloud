# 01 — Enable Data Streams (Data 360)

## Goal
Enable Data Streams so external guest and reservation data is ingested into Data 360.

## Steps Performed
1. App Launcher → Data Cloud
2. Data Streams tab → New
3. Source: Salesforce CRM (used as simulated external source)
4. Bundle: AIPlusData Custom Data Bundle
5. Deploy Data Streams
6. Refresh and run each stream using Refresh Now

## Validation
- Last Run Status = Success
- Total Records > 0

## Screenshot Proof
Add image:
- images/datastreams-success.png

