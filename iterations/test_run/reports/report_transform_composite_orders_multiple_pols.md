# Pruchase Orders and Purchase Order Lines Transformation Report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-05-09T11:14:28.233526+00:00   
Time Finished: | 2023-05-09T11:14:39.493347+00:00   
Elapsed time: | 0:00:11.259821   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 12 things</summary>     
   
Measure | Count   
--- | ---:   
DATA ISSUE Vendors not matched to FOLIO Organizations | 1   
FAILED Records failed due to an error | 1   
Instances not matched to migrated bib records | 24   
Notes without content that were discarded. Set some default value if you only intend to set the note title | 8   
Number of empty rows in sierra_orders_with_blanket_orders.tsv | 0   
Number of files processed | 1   
Number of rows in sierra_orders_with_blanket_orders.tsv | 9   
Rows merged to create Purchase Orders | 3   
TOTAL Purchase Order Lines created | 8   
TOTAL Purchase Orders created | 5   
Vendors matched to FOLIO Organizations | 8   
</details>   
   
## Mapping details    
    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Replaced b in FORM with Physical Resource | 24   
Replaced p in ORD TYPE with Ongoing | 4   
Replaced s in ORD TYPE with One-Time | 5   
</details>   
   
## POL Acquisition Method Mapping    
    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
p -> Purchase | 12   
s -> Purchase | 12   
</details>   
   
## POL location mapping    
This is the location for for the purchase order line.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) -- cjos  -> migration | 6   
Unmapped (Default value was set) -- maos  -> migration | 6   
Unmapped (Default value was set) -- masl  -> migration | 12   
</details>   
   
## Default values from mapping added    
The values below were added to all records from the 'value' field in the mapping file, overriding any mapped values from the source data.    
<details><summary>Click to expand all 5 things</summary>     
   
Measure | Count   
--- | ---:   
A migrated note added to notes[0].title | 8   
API added to compositePoLines[0].source | 24   
f5bba0d2-7732-4687-8311-a2cb0eaa12e5 added to notes[0].typeId | 8   
orders added to notes[0].domain | 8   
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
root['compositePoLines'][0]['instanceId'] | 3   
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
compositePoLines.instanceId | 7 (78%) | 2 (22%) 
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
ACQ TYPE | 24 (266.7%) | 24 (267%) | 0  
BLANKET PO | 33 (366.7%) | 33 (367%) | 0  
COPIES | 24 (266.7%) | 24 (267%) | 0  
FORM | 24 (266.7%) | 24 (267%) | 0  
LOCATION | 24 (266.7%) | 24 (267%) | 0  
ORD TYPE | 9 (100.0%) | 9 (100%) | 0  
RECORD #(BIBLIO) | 24 (266.7%) | 24 (267%) | 0  
TITLE | 24 (266.7%) | 24 (267%) | 0  
VENDOR | 8 (88.9%) | 8 (89%) | 0  
</details>   
