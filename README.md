# Uplink Scheduler Modification (OAI)

## Overview
The uplink scheduler in 5G NR is responsible for:
- Selecting which UEs transmit in each time slot
- Allocating Physical Resource Blocks (PRBs)
- Choosing Modulation and Coding Scheme (MCS)
- Managing power control parameters

It typically uses a Proportional Fair (PF) algorithm to balance throughput and fairness.

## My Contribution
- Modified the uplink scheduler in OpenAirInterface (OAI)
- Implemented a **static PRB allocation strategy** for two UEs
- Assigned **fixed and distinct PRB sets** to each UE
- Introduced **time-varying PRB patterns** to observe scheduler behavior

