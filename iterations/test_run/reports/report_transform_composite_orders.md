# Orders and Orderlines Transformation Report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-02-17T17:13:48.468540+00:00   
Time Finished: | 2023-02-17T17:15:27.397409+00:00   
Elapsed time: | 0:01:38.928869   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 6 things</summary>     
   
Measure | Count   
--- | ---:   
Empty rows in sierra_orders.tsv | 0   
Instance ID mapped from previously migrated bib records | 2   
Number of files processed | 1   
Number of objects in source data file | 1   
Total rows in sierra_orders.tsv | 1   
</details>   
   
## Default values added    
The values below was added to all records from the value field in the mapping file instead of coming from the source records    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
From Schema: approved -> False | 1   
From Schema: reEncumber -> False | 1   
From Schema: workflowStatus -> Pending | 1   
</details>   
   
## Mapping details    
    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Replaced s in ORD TYPE with Electronic Resource | 2   
Replaced s in ORD TYPE with One-Time | 1   
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
ORD TYPE | 1 (100.0%) | 1 (100%) | 0  
RECORD #(Order) | 1 (100.0%) | 1 (100%) | 0  
VENDOR | 1 (100.0%) | 1 (100%) | 0  
</details>   
