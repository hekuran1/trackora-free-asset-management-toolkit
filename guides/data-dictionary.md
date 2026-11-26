# Data Dictionary

Field guidance for `templates/asset-inventory.csv`. All sample rows are fictional.

| Field | Guidance |
|---|---|
| asset_tag | Unique, never reused (e.g. IT-0001) |
| category | Laptop, Phone, Monitor, AV, Tool, Furniture, Other |
| status | On order, In stock, In use, In repair, Retired, Disposed |
| condition | New, Good, Fair, Damaged |
| assigned_to | Person responsible; blank if in stock |
| purchase_date, warranty_expiry, last_audit_date | ISO format YYYY-MM-DD |
| purchase_cost, currency | Numeric amount and ISO code (USD, EUR) |
