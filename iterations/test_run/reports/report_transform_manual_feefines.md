# Manual fee/fine transformation report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-05-02T16:26:32.020911+00:00   
Time Finished: | 2023-05-02T16:26:39.907953+00:00   
Elapsed time: | 0:00:07.887042   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 9 things</summary>     
   
Measure | Count   
--- | ---:   
Empty rows in test_feefimes.tsv | 0   
Number of files processed | 1   
Number of records in total | 4   
Number of rows in source file | 4   
Records failed due to an error | 1   
Stored account | 3   
Stored feefineactions | 3   
Total rows in test_feefimes.tsv | 4   
</details>   
   
## Default values from mapping added    
The values below were added to all records from the 'value' field in the mapping file, overriding any mapped values from the source data.    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Open added to account.status.name | 3   
Outstanding added to account.paymentStatus.name | 3   
</details>   
   
## Fee/Fine Type mapping    
Reference data mapping for Fee/Fine types.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) -- other -> Other charges | 1   
card -> Replacement library card | 1   
spill -> Coffee spill | 1   
</details>   
   
## Fee/Fine Owner mapping    
Reference data mapping for Fee/Fine owners.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) -- library10 -> The Best Fee Fine Owner | 1   
Unmapped (Default value was set) -- library2 -> The Best Fee Fine Owner | 1   
library1 -> The Best Fee Fine Owner | 1   
</details>   
   
## FOLIO default values added    
The below FOLIO default values were added to records that had no mapped value in the source data.    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
 added to account.remaining | 1   
 added to feefineaction.comments | 3   
</details>   
   
## Fee/Fine Service Point mapping    
Reference data mapping for Fee/Fine service points.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) --  -> Migration | 1   
desk1 -> Library Main Desk | 1   
desk2 -> Finance Office | 1   
</details>   

## Mapped FOLIO fields
<details><summary>Click to expand field report</summary>     

FOLIO Field | Mapped | Unmapped  
--- | --- | ---:  
account | 3 (0%) | 0 (0%) 
account.amount | 3 (0%) | 0 (0%) 
account.barcode | 3 (0%) | 0 (0%) 
account.callNumber | 3 (0%) | 0 (0%) 
account.feeFineId | 3 (0%) | 0 (0%) 
account.feeFineOwner | 3 (0%) | 0 (0%) 
account.feeFineType | 3 (0%) | 0 (0%) 
account.id | 3 (0%) | 0 (0%) 
account.itemId | 3 (0%) | 0 (0%) 
account.location | 3 (0%) | 0 (0%) 
account.materialType | 3 (0%) | 0 (0%) 
account.materialTypeId | 3 (0%) | 0 (0%) 
account.ownerId | 3 (0%) | 0 (0%) 
account.paymentStatus | 3 (0%) | 0 (0%) 
account.paymentStatus.name | 3 (0%) | 0 (0%) 
account.remaining | 3 (0%) | 0 (0%) 
account.status | 3 (0%) | 0 (0%) 
account.status.name | 3 (0%) | 0 (0%) 
account.title | 3 (0%) | 0 (0%) 
account.userId | 3 (0%) | 0 (0%) 
feefineaction | 3 (0%) | 0 (0%) 
feefineaction.accountId | 3 (0%) | 0 (0%) 
feefineaction.amountAction | 3 (0%) | 0 (0%) 
feefineaction.balance | 3 (0%) | 0 (0%) 
feefineaction.comments | 3 (0%) | 0 (0%) 
feefineaction.createdAt | 3 (0%) | 0 (0%) 
feefineaction.dateAction | 3 (0%) | 0 (0%) 
feefineaction.id | 3 (0%) | 0 (0%) 
feefineaction.source | 3 (0%) | 0 (0%) 
feefineaction.typeAction | 3 (0%) | 0 (0%) 
feefineaction.userId | 3 (0%) | 0 (0%) 
</details>   

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>     

Legacy Field | Present | Mapped | Unmapped  
--- | --- | --- | ---:  
amount | 4 (0.0%) | 4 (0%) | 0  
billed_date | 4 (0.0%) | 4 (0%) | 0  
borrowing_desk | 4 (0.0%) | 3 (0%) | 1  
item_barcode | 4 (0.0%) | 4 (0%) | 0  
lending_library | 4 (0.0%) | 4 (0%) | 0  
patron_barcode | 4 (0.0%) | 4 (0%) | 0  
remaining | 4 (0.0%) | 3 (0%) | 1  
type | 4 (0.0%) | 4 (0%) | 0  
</details>   
