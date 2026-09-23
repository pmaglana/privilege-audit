<a id="top"></a>
<!---
# PRIVILEGE AUDIT


## Scenario


## Objective


## Scope and methodology

| Method               | Sees                                        | Misses                              |
|----------------------|---------------------------------------------|-------------------------------------|
| IAM blade / export   | Active assignments at scope, inherited      | Group members, orphaned principals  |
| Azure CLI            | Same, plus null principalName (orphans)     | One scope per run                   |
| Resource Graph (KQL) | Whole tenant in one query                   | Eligible assignments                |
| PIM export           | Eligible vs active, activation history      | Assignments outside PIM             |



## Findings, severity-ranked



## Audit Path


### Finding 1: Access Control (IAM) blade


### Finding 2: Azure CLI


### Finding 3: Azure Resource Graph with KQL


### Finding 4: Privileged Identity Management export


### Finding 5: The Hunt



## Why the orphan matters at all? //REPHRASE: Make it less technical


## Recommendations


## Overall Assessment
--->



# THE PRIVILEGE AUDIT

## Executive summary

## Scope
Tenant</br>
Clearance</br>
Environment</br>
Objective</br>
  
## Methodology
<!--- Methodology Comparison Table?? --->

| Method               | Sees                                        | Misses                              |
|----------------------|---------------------------------------------|-------------------------------------|
| IAM blade / export   | Active assignments at scope, inherited      | Group members, orphaned principals  |
| Azure CLI            | Same, plus null principalName (orphans)     | One scope per run                   |
| Resource Graph (KQL) | Whole tenant in one query                   | Eligible assignments                |
| PIM export           | Eligible vs active, activation history      | Assignments outside PIM             |

## Findings Summary

| Finding | Issue Identified | Security Concern |
|---|---|---|
| Finding 1 | TBD | TBD |
| Finding 2 | TBD | TBD |
| Finding 3 | TBD | TBD |
| Finding 4 | TBD | TBD |
| Finding 5 | TBD | TBD |

### Finding 1: Access Control (IAM) Blade
- Observation
- Evidence
- Finding
- Security Impact
- Recommendation

### Finding 2: Azure CLI
- Observation
- Evidence
- Finding
- Security Impact
- Recommendation

### Finding 3: Azure Resource Graph with KQL
- Observation
- KQL
- Finding
- Security Impact
- Recommendation

### Finding 4: Privileged Identity Management
- Observation
- Evidence
- Finding
- Security Impact
- Recommendation

### Finding 5: The Hunt
- Observation
- Evidence
- Finding
- Security Impact
- Recommendation

## Audit Observations

## Why Orphaned Access Matters

## Overall Recommendations and Assessment
<!---
The audit identified several Azure RBAC access-management issues, including stale or orphaned assignments and permissions that should be reviewed against least-privilege principles. These findings demonstrate the importance of regularly reviewing both active and eligible access across the environment.

The organization should establish a recurring RBAC access review process that includes inherited permissions, deleted or inactive identities, excessive privileges, and PIM assignments. Privileged access should be minimized where possible and managed through Microsoft Entra ID PIM to support just-in-time access and reduce unnecessary standing permissions.
--->


</br>

<sub>[⬆️ Back to Top](#top)</sub>
