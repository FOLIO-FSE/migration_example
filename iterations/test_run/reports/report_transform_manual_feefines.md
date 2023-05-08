# Manual fee/fine transformation report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-05-05T11:50:11.331844+00:00   
Time Finished: | 2023-05-05T11:50:26.047931+00:00   
Elapsed time: | 0:00:14.716087   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 11 things</summary>     
   
Measure | Count   
--- | ---:   
DATA ISSUE Invalid dates | 1   
DATA ISSUE Invalid sum | 1   
DATA ISSUE Items not in FOLIO | 4   
DATA ISSUE Users not in FOLIO | 1   
FAILED Records failed due to an error | 2   
Number of empty rows in test_feefines.tsv | 1   
Number of files processed | 1   
Number of rows in test_feefines.tsv | 7   
TOTAL Accounts created | 4   
TOTAL Feefineactions created | 4   
</details>   
   
## Default values from mapping added    
The values below were added to all records from the 'value' field in the mapping file, overriding any mapped values from the source data.    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Open added to account.status.name | 5   
Outstanding added to account.paymentStatus.name | 5   
</details>   
   
## Fee/Fine Type mapping    
Reference data mapping for Fee/Fine types.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) -- other -> Other charges | 2   
card -> Replacement library card | 2   
spill -> Coffee spill | 1   
</details>   
   
## Fee/Fine Owner mapping    
Reference data mapping for Fee/Fine owners.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) -- library10 -> The Best Fee Fine Owner | 1   
Unmapped (Default value was set) -- library2 -> The Best Fee Fine Owner | 2   
library1 -> The Best Fee Fine Owner | 2   
</details>   
   
## FOLIO default values added    
The below FOLIO default values were added to records that had no mapped value in the source data.    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
 added to feefineaction.comments | 5   
</details>   
   
## Fee/Fine Service Point mapping    
Reference data mapping for Fee/Fine service points.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) --  -> Migration | 1   
desk1 -> Library Main Desk | 2   
desk2 -> Finance Office | 2   
</details>   

## Mapped FOLIO fields
<details><summary>Click to expand field report</summary>     

FOLIO Field | Mapped | Unmapped  
--- | --- | ---:  
account | 4 (0%) | 0 (0%) 
account.amount | 4 (0%) | 0 (0%) 
account.feeFineId | 4 (0%) | 0 (0%) 
account.feeFineOwner | 4 (0%) | 0 (0%) 
account.feeFineType | 4 (0%) | 0 (0%) 
account.id | 4 (0%) | 0 (0%) 
account.ownerId | 4 (0%) | 0 (0%) 
account.paymentStatus | 4 (0%) | 0 (0%) 
account.paymentStatus.name | 4 (0%) | 0 (0%) 
account.remaining | 4 (0%) | 0 (0%) 
account.status | 4 (0%) | 0 (0%) 
account.status.name | 4 (0%) | 0 (0%) 
account.userId | 4 (0%) | 0 (0%) 
feefineaction | 4 (0%) | 0 (0%) 
feefineaction.accountId | 4 (0%) | 0 (0%) 
feefineaction.amountAction | 4 (0%) | 0 (0%) 
feefineaction.balance | 4 (0%) | 0 (0%) 
feefineaction.comments | 4 (0%) | 0 (0%) 
feefineaction.createdAt | 4 (0%) | 0 (0%) 
feefineaction.dateAction | 3 (0%) | 0 (0%) 
feefineaction.id | 4 (0%) | 0 (0%) 
feefineaction.source | 4 (0%) | 0 (0%) 
feefineaction.typeAction | 4 (0%) | 0 (0%) 
feefineaction.userId | 4 (0%) | 0 (0%) 
id | 4 (0%) | 0 (0%) 
</details>   

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>     

Legacy Field | Present | Mapped | Unmapped  
--- | --- | --- | ---:  
amount | 6 (0.0%) | 6 (0%) | 0  
billed_date | 6 (0.0%) | 6 (0%) | 0  
borrowing_desk | 6 (0.0%) | 5 (0%) | 1  
item_barcode | 6 (0.0%) | 6 (0%) | 0  
lending_library | 6 (0.0%) | 6 (0%) | 0  
patron_barcode | 6 (0.0%) | 6 (0%) | 0  
remaining | 6 (0.0%) | 6 (0%) | 0  
type | 6 (0.0%) | 6 (0%) | 0  
</details>   
