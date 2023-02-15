# Loans migration report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-01-31T14:32:11.778609+00:00   
Time Finished: | 2023-01-31T14:39:20.406885+00:00   
Elapsed time: | 0:07:08.628276   
   
##     
    
<details><summary>Click to expand all 8 things</summary>     
   
Measure | Count   
--- | ---:   
Empty rows in loans.tsv | 0   
Failed loans | 8   
Loans failed pre-validation | 5   
Loans verified against migrated user and item | 9   
Processed pre-validated loans | 9   
Successfully checked out | 9   
Total rows in loans.tsv | 17   
Updated renewal count for loan | 6   
</details>   
   
## Details    
    
<details><summary>Click to expand all 7 things</summary>     
   
Measure | Count   
--- | ---:   
Checked out on first try | 9   
Hour and minute not specified for due date. Assuming end of local calendar day (23:59)... | 1   
Provided due_date is not UTC, setting tzinfo to tenant timezone (UTC) | 17   
Provided out_date is not UTC, setting tzinfo to tenant timezone (UTC) | 17   
Successfully updated open loan (204) | 6   
Update open loan error http status: 500 | 3   
</details>   
   
## Discarded loans    
List of loans discarded for various resons    
<details><summary>Click to expand all 6 things</summary>     
   
Measure | Count   
--- | ---:   
Empty properties in legacy data - patron_barcode | 1   
Loans discarded. Had migrated item barcode: False. Had migrated user barcode: False | 1   
Loans discarded. Had migrated item barcode: False. Had migrated user barcode: True | 2   
Not an allowed status - Missing | 3   
Time alignment issues - both dates | 1   
</details>   
