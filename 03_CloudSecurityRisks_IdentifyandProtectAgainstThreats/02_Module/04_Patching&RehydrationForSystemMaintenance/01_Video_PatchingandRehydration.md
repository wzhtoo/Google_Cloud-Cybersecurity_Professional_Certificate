# 01_Patching and rehydration

[Patching and rehydration 🔗](https://www.coursera.org/learn/cloud-security-risks-identify-and-protect-against-threats/lecture/mPWZM/patching-and-rehydration)

## Patching

The process of installing updates to software to address vulnerabilities, improve stability, or add new features

## Mechanics of patching

- Develop a cloud-based inventory and baseline
- Identify vulnerabilities and available patches for the system
- Assess the patch's impace on the system
- Download and test teh patch in a non-production environment
- Schedule the downtime or plan a service restart
- Backup data and system configurations
- Apply the patch to the system
- Verify the patch's effectiveness and stability

## Rehydration

A cloud-native process where new servers are created with the latest updates and patches, allowing for the workload to the transferred from old servers, and for the outdated servers to be decommissioned or destroyed

## Mechanics of rehydration

- Inventory all resources
- Identify vulnerabilities
- Run updated and old instances to compare
- Redirect traffic from old to new instances
- Decommission or destroy old instances
