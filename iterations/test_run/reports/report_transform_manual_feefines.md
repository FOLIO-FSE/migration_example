# Manual fees/fines migration report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-04-28T15:07:44.224811+00:00   
Time Finished: | 2023-04-28T15:07:47.304234+00:00   
Elapsed time: | 0:00:03.079423   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 8 things</summary>     
   
Measure | Count   
--- | ---:   
Empty rows in test_feefimes.tsv | 0   
Number of files processed | 1   
Number of records in total | 3   
Number of rows in source file | 3   
Stored account | 3   
Stored feefineactions | 3   
Total rows in test_feefimes.tsv | 3   
</details>   
   
## Unmapped properties    
    
<details><summary>Click to expand all 33 things</summary>     
   
Measure | Count   
--- | ---:   
account.barcode | 3   
account.callNumber | 3   
account.contributors | 3   
account.dateCreated | 3   
account.dateUpdated | 3   
account.dueDate | 3   
account.feeFineOwner | 3   
account.feeFineType | 3   
account.holdingsRecordId | 3   
account.instanceId | 3   
account.itemStatus.name | 3   
account.loanId | 3   
account.loanPolicyId | 3   
account.location | 3   
account.lostItemFeePolicyId | 3   
account.materialType | 3   
account.materialTypeId | 3   
account.metadata | 3   
account.overdueFinePolicyId | 3   
account.processId | 3   
account.returnedDate | 3   
account.status.name | 3   
account.title | 3   
feefineaction.amountAction | 3   
feefineaction.balance | 3   
feefineaction.comments | 3   
feefineaction.createdAt | 3   
feefineaction.notify | 3   
feefineaction.paymentMethod | 3   
feefineaction.source | 3   
feefineaction.transactionInformation | 3   
feefineaction.typeAction | 3   
</details>   
   
## Default values from mapping added    
The values below were added to all records from the 'value' field in the mapping file, overriding any mapped values from the source data.    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Outstanding added to account.paymentStatus.name | 3   
</details>   
   
## Fee/Fyne Type mapping    
Reference data mapping for Fee/Fine Types.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) -- other -> Replacement library card | 1   
card -> Replacement library card | 1   
spill -> Coffee spill | 1   
</details>   
   
## Fee/Fine Owner mapping    
Reference data mapping for Fee/Fine Owners.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) -- library5 -> The Other Fee Fine Owner | 1   
library1 -> The Best Fee Fine Owner | 1   
library2 -> The Other Fee Fine Owner | 1   
</details>   
   
## FOLIO default values added    
The below FOLIO default values were added to records that had no mapped value in the source data.    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
 added to feefineaction.comments | 3   
</details>   
