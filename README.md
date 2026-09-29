# Implement Client Script & UI Policy - Incident Table
Platform: ServiceNow
Table: Incident [incident]

Objective: To improve UX and data quality on Incident form using Client Scripts and UI Policies.

Client Scripts:
1. Make Priority mandatory when Urgency is High
2. Auto-populate Assignment Group based on Category
3. Alert when Short Description is too short

UI Policies:
1. Major Incident Fields - Show Major Incident details when Major Incident checkbox is true
2. Hardware Category - Make Subcategory mandatory and show CI field when Category=Hardware
3. Readonly Close Fields on Resolved
