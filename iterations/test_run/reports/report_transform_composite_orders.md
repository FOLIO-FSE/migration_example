# Orders and Orderlines Transformation Report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-03-21T13:23:34.481259+00:00   
Time Finished: | 2023-03-21T13:23:48.518869+00:00   
Elapsed time: | 0:00:14.037610   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 7 things</summary>     
   
Measure | Count   
--- | ---:   
Empty rows in sierra_orders.tsv | 0   
Instance ID mapped from previously migrated bib records | 6   
Number of files processed | 1   
PO-lines merged into one PO | 1   
Successfully matched Vendor against code | 3   
Total rows in sierra_orders.tsv | 3   
</details>   
   
## Default values added    
The values below was added to all records from the value field in the mapping file instead of coming from the source records    
<details><summary>Click to expand all 6 things</summary>     
   
Measure | Count   
--- | ---:   
API added to compositePoLines[0].source | 6   
From Schema: approved -> False | 3   
From Schema: reEncumber -> False | 3   
From Schema: workflowStatus -> Pending | 3   
USD added to compositePoLines[0].cost.currency | 6   
</details>   
   
## Mapping details    
    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Replaced s in ORD TYPE with Electronic Resource | 6   
Replaced s in ORD TYPE with One-Time | 3   
</details>   
   
## Differences between generated orders with same Legacy Identifier    
This is a technical report that helps you to identify differences in the mapped order fields.     
<details><summary>Click to expand all 5 things</summary>     
   
Measure | Count   
--- | ---:   
root['compositePoLines'][0]['instanceId'] | 1   
root['compositePoLines'][0]['titleOrPackage'] | 1   
root['metadata']['createdDate'] | 2   
root['metadata']['updatedDate'] | 2   
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
ORD TYPE | 3 (100.0%) | 3 (100%) | 0  
RECORD #(Order) | 3 (100.0%) | 3 (100%) | 0  
VENDOR | 3 (100.0%) | 3 (100%) | 0  
</details>   
