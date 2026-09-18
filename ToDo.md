#To Do list

## DB rules yet to be established 

- part_id must be unique
- library_ref must not be NULL
- status must be one of allowed states
- every parameter must belong to a valid component
- every footprint association must belong to a valid component

## DB mismatches

Component | DB/SchLib footprint reference | Physical PcbLib | Action
----------|-------------------------------|-----------------|--------
-MZQ-000009 | FP-S10B-PHDSS_LF_SN-MFG | Missing | Still unresolved; create/validate correct footprint

Also found these physical footprints in Orion's PcbLib that no current database component references:

- ESP32-C5-WROOM-1U
- FP-LTST-C190GKT-MFG
- FP-SRN8040-MFG
- FP-TAJB-MFG
- FP-TL1015AF160QG-MFG
- TP06R
