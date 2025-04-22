# Splunk Basics Lab - April 2025

## What I Did
- Installed Splunk Enterprise locally
- Uploaded sample web server logs (`sample_web_log.log`)
- Indexed logs using manual source type: `access_combined`
- Ran basic SPL (Search Processing Language) queries

---

## SPL Queries Used
1. `index=main`
2. `index=main "failed login"`
3. `index=main | stats count by src_ip`
4. `index=main | stats count by sourcetype`


## What I Learned / Observations
- How to upload and index log data in Splunk
- What source types do and how to select the right one
- Basic log search using SPL
- How to view log events and field extractions

## Next Steps
- Simulate a brute-force login attack (TryHackMe lab or local logs)
- Detect suspicious IPs with SPL queries
- Create alerts and dashboards in Splunk
