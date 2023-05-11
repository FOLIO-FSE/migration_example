# Pruchase Orders and Purchase Order Lines Transformation Report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-05-11T12:45:31.926086+00:00   
Time Finished: | 2023-05-11T12:45:43.895980+00:00   
Elapsed time: | 0:00:11.969894   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 9 things</summary>     
   
Measure | Count   
--- | ---:   
FAILED Records failed due to an error | 1   
Number of discarded notes with no content | 8   
Number of empty rows in sierra_orders_with_blanket_orders.tsv | 0   
Number of files processed | 1   
Number of rows in sierra_orders_with_blanket_orders.tsv | 9   
Rows merged to create Purchase Orders | 3   
TOTAL Purchase Order Lines created | 8   
TOTAL Purchase Orders created | 5   
</details>   
   
## Mapping details    
    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Replaced b in FORM with Physical Resource | 27   
Replaced p in ORD TYPE with Ongoing | 4   
Replaced s in ORD TYPE with One-Time | 5   
</details>   
   
## POL Acquisition Method Mapping    
    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) -- v -> Other | 3   
p -> Purchase | 21   
s -> Purchase | 3   
</details>   
   
## POL location mapping    
This is the location for for the purchase order line.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) -- cjos  -> migration | 6   
Unmapped (Default value was set) -- maos  -> migration | 9   
Unmapped (Default value was set) -- masl  -> migration | 12   
</details>   
   
## Default values from mapping added    
The values below were added to all records from the 'value' field in the mapping file, overriding any mapped values from the source data.    
<details><summary>Click to expand all 5 things</summary>     
   
Measure | Count   
--- | ---:   
A migrated note added to notes[0].title | 8   
API added to compositePoLines[0].source | 27   
f5bba0d2-7732-4687-8311-a2cb0eaa12e5 added to notes[0].typeId | 8   
orders added to notes[0].domain | 8   
</details>   
   
## Linked Organizations    
All purchase orders must be linked to an organization.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
LINKING FAILED Organization identifier not in ID map/FOLIO | 1   
Organizations linked using organizations_id_map | 9   
Organizations not in ID map, linked using FOLIO lookup | 1   
</details>   
   
## Linked Instances    
Purchase Oreder Lines can but do not have to be linked to instances    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Instance linked using instances_id_map | 1   
Istance not linked - bib identifier not in instances_id_map | 7   
</details>   
   
## FOLIO default values added    
The below FOLIO default values were added to records that had no mapped value in the source data.    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
 added to compositePoLines[0].instanceId | 3   
 added to notes[0].content | 8   
</details>   
   
## Differences between generated orders with same Legacy Identifier    
This is a technical report that helps you to identify differences in the mapped order fields.     
<details><summary>Click to expand all 11 things</summary>     
   
Measure | Count   
--- | ---:   
root['compositePoLines'][0]['cost']['currency'] | 1   
root['compositePoLines'][0]['cost']['poLineEstimatedPrice'] | 3   
root['compositePoLines'][0]['cost']['quantityPhysical'] | 1   
root['compositePoLines'][0]['id'] | 3   
root['compositePoLines'][0]['instanceId'] | 2   
root['compositePoLines'][0]['locations'][0]['quantity'] | 1   
root['compositePoLines'][0]['titleOrPackage'] | 3   
root['compositePoLines'][1] | 1   
root['metadata']['createdDate'] | 3   
root['metadata']['updatedDate'] | 3   
</details>   

## Mapped FOLIO fields
<details><summary>Click to expand field report</summary>     

FOLIO Field | Mapped | Unmapped  
--- | --- | ---:  
acqUnitIds | 0 (0%) | 9 (100%) 
approvalDate | 0 (0%) | 9 (100%) 
approved | 0 (0%) | 9 (100%) 
approvedById | 0 (0%) | 9 (100%) 
assignedTo | 0 (0%) | 9 (100%) 
billTo | 0 (0%) | 9 (100%) 
closeReason | 0 (0%) | 9 (100%) 
compositePoLines | 8 (89%) | 1 (11%) 
compositePoLines.acquisitionMethod | 8 (89%) | 1 (11%) 
compositePoLines.cost | 8 (89%) | 1 (11%) 
compositePoLines.cost.currency | 8 (89%) | 1 (11%) 
compositePoLines.cost.poLineEstimatedPrice | 8 (89%) | 1 (11%) 
compositePoLines.cost.quantityPhysical | 8 (89%) | 1 (11%) 
compositePoLines.id | 8 (89%) | 1 (11%) 
compositePoLines.instanceId | 1 (11%) | 8 (89%) 
compositePoLines.locations | 8 (89%) | 1 (11%) 
compositePoLines.locations.locationId | 8 (89%) | 1 (11%) 
compositePoLines.locations.quantity | 8 (89%) | 1 (11%) 
compositePoLines.orderFormat | 8 (89%) | 1 (11%) 
compositePoLines.source | 8 (89%) | 1 (11%) 
compositePoLines.titleOrPackage | 8 (89%) | 1 (11%) 
dateOrdered | 0 (0%) | 9 (100%) 
id | 8 (89%) | 1 (11%) 
manualPo | 0 (0%) | 9 (100%) 
metadata | 8 (89%) | 1 (11%) 
metadata.createdByUserId | 8 (89%) | 1 (11%) 
metadata.createdDate | 8 (89%) | 1 (11%) 
metadata.updatedByUserId | 8 (89%) | 1 (11%) 
metadata.updatedDate | 8 (89%) | 1 (11%) 
needReEncumber | 0 (0%) | 9 (100%) 
notes | 0 (0%) | 9 (100%) 
ongoing | 0 (0%) | 9 (100%) 
orderType | 8 (89%) | 1 (11%) 
poNumber | 8 (89%) | 1 (11%) 
poNumberPrefix | 0 (0%) | 9 (100%) 
poNumberSuffix | 0 (0%) | 9 (100%) 
reEncumber | 0 (0%) | 9 (100%) 
shipTo | 0 (0%) | 9 (100%) 
tags | 0 (0%) | 9 (100%) 
template | 0 (0%) | 9 (100%) 
totalEncumbered | 0 (0%) | 9 (100%) 
totalEstimatedPrice | 0 (0%) | 9 (100%) 
totalExpended | 0 (0%) | 9 (100%) 
totalItems | 0 (0%) | 9 (100%) 
vendor | 8 (89%) | 1 (11%) 
workflowStatus | 0 (0%) | 9 (100%) 
</details>   

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>     

Legacy Field | Present | Mapped | Unmapped  
--- | --- | --- | ---:  
ACQ TYPE | 27 (300.0%) | 27 (300%) | 0  
BLANKET PO | 36 (400.0%) | 36 (400%) | 0  
COPIES | 27 (300.0%) | 27 (300%) | 0  
FORM | 27 (300.0%) | 27 (300%) | 0  
LOCATION | 27 (300.0%) | 27 (300%) | 0  
ORD TYPE | 9 (100.0%) | 9 (100%) | 0  
RECORD #(BIBLIO) | 27 (300.0%) | 27 (300%) | 0  
TITLE | 27 (300.0%) | 27 (300%) | 0  
VENDOR | 9 (100.0%) | 9 (100%) | 0  
</details>   
