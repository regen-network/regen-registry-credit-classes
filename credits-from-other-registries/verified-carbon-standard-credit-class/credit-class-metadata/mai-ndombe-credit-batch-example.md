---
description: >-
  This is a first example of what project and batch metadata will look like for
  Verra credits sold on regen ledger.
---

# Mai Ndombe Credit Batch Example

### Project Metadata&#x20;

```json
{
    "verra_project_id": 934, 
    "verra_project_page": "https://registry.verra.org/app/projectDetail/VCS/934",
    "project_proponent": "Wildlife Works Carbon LLC", 
    "VCS_project_type": "Agriculture Forestry and Other Land Use",
    "project_activity": "REDD",
    "vcs_methodology": "VM0009",
    "project_size_ha": 299640,
    "project_start_date": "03-14-2011", 
    "project_end_date": "03-13-2041", 
    "offset_type": "avoided emissions"
}
```

### Credit Batch Metadata

in the batch metadata there is a clear indicator what the project id is so there is a clear path to migrate the information&#x20;

```json
{
    // url for verra to project page 
    "verra_project_page": "https://registry.verra.org/app/projectDetail/VCS/934",
    
    // verra retirement serial number for this batch issuance
    "verra_retirement_SN": "",
    
    // credit vintage 
    "vintage_year": "",
    
    // monitoring report for batch issuance
    "batch_monitoring_report": "",
    
    // verification report for batch issuance
    "batch_verification_report": "",
    
    // additional project information
    "verra_project_id": 934, 
    "verra_project_page": "https://registry.verra.org/app/projectDetail/VCS/934",
    "project_proponent": "Wildlife Works Carbon LLC", 
    "VCS_project_type": "Agriculture Forestry and Other Land Use",
    "project_activity": "REDD",
    "vcs_methodology": "VM0009",
    "project_size_ha": 299640,
    "project_start_date": "03-14-2011", 
    "project_end_date": "03-13-2041", 
    "offset_type": "avoided emissions"
}

```

### Verra Retirement Reason

```json
{
    "regen_credit_class_id": 1,
    "issuer_address": 2,
    "retiree_address": 3,
}
```
