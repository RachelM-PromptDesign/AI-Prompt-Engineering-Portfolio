#### 3. `Workflow_Automation/VyneTracker_AI_Conversion.md`  
```markdown
# Vyne Tracker Fax System → AI Automation

## AI Extraction Prompt
```prompt
Extract structured data from fax logs:
{ 
  "fax_datetime": "MM/DD/YYYY HH:MM AM/PM",
  "mrn": "8-digit number",
  "patient_name": "Last, First",
  "dob": "MM/DD/YYYY",
  "dos": "MM/DD/YYYY"
}

Rules:
- Return "N/A" for missing fields
- Flag mismatched formats
- Never hallucinate data
