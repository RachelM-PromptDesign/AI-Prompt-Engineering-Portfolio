# Vyne Tracker Fax System → AI Automation
## Original Template Fields
- Fax Date/Time
- MRN
- Patient Name
- DOB
- DOS (Date of Service)
## AI-Powered Prompt
```prompt
Extract structured data from fax logs:
{ "fax_datetime": "MM/DD/YYYY HH:MM AM/PM",
  "mrn": "8-digit number",
  "patient_name": "Last, First",
  "dob": "MM/DD/YYYY",
  "dos": "MM/DD/YYYY"}
Rules:
- Return "N/A" for missing fields
- Never hallucinate data
- Flag mismatched formats for human review
