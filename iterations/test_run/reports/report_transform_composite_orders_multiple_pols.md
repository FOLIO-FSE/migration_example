# Orders and Orderlines Transformation Report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-05-09T09:23:42.661179+00:00   
Time Finished: | 2023-05-09T09:23:54.323411+00:00   
Elapsed time: | 0:00:11.662232   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 9 things</summary>     
   
Measure | Count   
--- | ---:   
Bib id not found in list over migrated bibs. | 24   
Empty rows in sierra_orders_with_blanket_orders.tsv | 0   
Notes without content that were discarded. Set some default value if you only intend to set the note title | 8   
Number of files processed | 1   
Orders written to disk | 4   
PO-lines merged into one PO | 3   
Successfully matched Vendor against code | 8   
Total rows in sierra_orders_with_blanket_orders.tsv | 8   
</details>   
   
## Mapping details    
    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Replaced b in FORM with Physical Resource | 24   
Replaced p in ORD TYPE with Ongoing | 3   
Replaced s in ORD TYPE with One-Time | 5   
</details>   
   
## Order line location mapping    
This is the holdings location for for the order line (used to create holdings records if settings are configured to do so)    
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
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
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
</details>   

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>     

Legacy Field | Present | Mapped | Unmapped  
--- | --- | --- | ---:  
BLANKET PO | 32 (400.0%) | 32 (400%) | 0  
COPIES | 24 (300.0%) | 24 (300%) | 0  
FORM | 24 (300.0%) | 24 (300%) | 0  
LOCATION | 24 (300.0%) | 24 (300%) | 0  
ORD TYPE | 32 (400.0%) | 32 (400%) | 0  
RECORD #(BIBLIO) | 24 (300.0%) | 24 (300%) | 0  
TITLE | 24 (300.0%) | 24 (300%) | 0  
VENDOR | 8 (100.0%) | 8 (100%) | 0  
</details>   
