---
layout: page
title: Data
---

TNG subhalo matching catalog between high- and low-resolution runs
-------------
See Jung+ (2023) for more details. Citation to the paper is requested if you use these data catalogs. 
[Download](./dataset/dummy1.txt)

| Field | Description                                                                                                                                                      |
|-------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| id1   | SubhaloID in TNG100-1/TNG50-1                                                                                                                                    |
| id2   | SubhaloID in TNG100-2/TNG50-2                                                                                                                                    |
| prob1 | Probability of matching prediction from TNG100-1/TNG50-1 to TNG100-2/TNG50-2                                                                                     |
| prob2 | Probability of matching prediction from TNG100-1/TNG50-1 to TNG100-2/TNG50-2                                                                                     |
| flag  | We recommend excluding the subhalo pair with flag=0. Subhalos with M_DM > 3e9 Msun (or 3e8 Msun for TNG50) and min(prob1, prob2) > 0.7 are marked as one. |


Corrected subhalo properties for TNG300-1
-------------
See Jung+ (2023) for more details. Citation to the paper is requested if you use these data catalogs.

The corrected properties for the three fields: 'SubhaloMassType0', 'SubhaloMassType1', and 'SubhaloGasMetallicity', are available. All the subhalos with M_DM > 3e9 Msun are included. The units are the same as those used for the corresponding fields in the TNG collaboration.
[Download](./dataset/dummy1.txt)


