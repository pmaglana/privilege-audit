<a id="top"></a>
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



</br>

<sub>[⬆️ Back to Top](#top)</sub>
