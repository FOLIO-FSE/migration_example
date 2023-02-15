# Holdings transformation report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-01-31T08:10:53.570656+00:00   
Time Finished: | 2023-01-31T08:11:00.667095+00:00   
Elapsed time: | 0:00:07.096439   
   
## Holdings Merging    
    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Previously transformed holdings record loaded | 4   
callNumber empty or not set | 3   
</details>   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 10 things</summary>     
   
Measure | Count   
--- | ---:   
Empty rows in csv_items.tsv | 0   
Holdings Records Written to disk | 6   
Holdings already created from Item | 1   
Number of Legacy items in file | 3   
Number of files processed | 1   
Records matched to Instances | 3   
Total rows in csv_items.tsv | 3   
Unique Holdings created from Items | 2   
Unique ID:s written to legacy map | 9   
</details>   
   
## Bound-with mapping    
    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Number of bib records referenced in item: 1 | 3   
</details>   
   
## Location mapping    
These are the results for the mapping between legacy locations and your new FOLIO location structure    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) -- MAIN - ACDPM -> migration | 2   
Unmapped (Default value was set) -- REN - ACDPM -> migration | 1   
</details>   
   
## Default values added    
The values below was added to all records from the value field in the mapping file instead of coming from the source records    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
True added to notes[0].staffOnly | 3   
f453de0f-8b54-4e99-9180-52932529e3a6 added to notes[0].holdingsNoteTypeId | 3   
</details>   

## Mapped FOLIO fields
<details><summary>Click to expand field report</summary>     

FOLIO Field | Mapped | Unmapped  
--- | --- | ---:  
_version | 0 (0%) | 3 (100%) 
acquisitionFormat | 0 (0%) | 3 (100%) 
acquisitionMethod | 0 (0%) | 3 (100%) 
administrativeNotes | 0 (0%) | 3 (100%) 
bareHoldingsItems | 0 (0%) | 3 (100%) 
callNumber | 0 (0%) | 3 (100%) 
callNumberPrefix | 0 (0%) | 3 (100%) 
callNumberSuffix | 0 (0%) | 3 (100%) 
callNumberTypeId | 0 (0%) | 3 (100%) 
copyNumber | 0 (0%) | 3 (100%) 
digitizationPolicy | 0 (0%) | 3 (100%) 
discoverySuppress | 0 (0%) | 3 (100%) 
effectiveLocationId | 0 (0%) | 3 (100%) 
electronicAccess | 0 (0%) | 3 (100%) 
formerIds | 3 (100%) | 0 (0%) 
holdingsInstance | 0 (0%) | 3 (100%) 
holdingsItems | 0 (0%) | 3 (100%) 
holdingsStatements | 3 (100%) | 0 (0%) 
holdingsStatements.statement | 3 (100%) | 0 (0%) 
holdingsStatementsForIndexes | 0 (0%) | 3 (100%) 
holdingsStatementsForSupplements | 0 (0%) | 3 (100%) 
holdingsTypeId | 3 (100%) | 0 (0%) 
hrid | 0 (0%) | 3 (100%) 
id | 3 (100%) | 0 (0%) 
illPolicy | 0 (0%) | 3 (100%) 
illPolicyId | 0 (0%) | 3 (100%) 
instanceId | 3 (100%) | 0 (0%) 
metadata | 3 (100%) | 0 (0%) 
metadata.createdByUserId | 3 (100%) | 0 (0%) 
metadata.createdDate | 3 (100%) | 0 (0%) 
metadata.updatedByUserId | 3 (100%) | 0 (0%) 
metadata.updatedDate | 3 (100%) | 0 (0%) 
notes | 3 (100%) | 0 (0%) 
notes.holdingsNoteTypeId | 3 (100%) | 0 (0%) 
notes.note | 3 (100%) | 0 (0%) 
notes.staffOnly | 3 (100%) | 0 (0%) 
numberOfItems | 0 (0%) | 3 (100%) 
permanentLocation | 0 (0%) | 3 (100%) 
permanentLocationId | 3 (100%) | 0 (0%) 
receiptStatus | 0 (0%) | 3 (100%) 
receivingHistory | 0 (0%) | 3 (100%) 
retentionPolicy | 0 (0%) | 3 (100%) 
shelvingTitle | 0 (0%) | 3 (100%) 
sourceId | 3 (100%) | 0 (0%) 
statisticalCodeIds | 0 (0%) | 3 (100%) 
tags | 0 (0%) | 3 (100%) 
temporaryLocationId | 0 (0%) | 3 (100%) 
</details>   

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>     

Legacy Field | Present | Mapped | Unmapped  
--- | --- | --- | ---:  
PERM_LOCATION | 3 (100.0%) | 3 (100%) | 0  
Z30_REC_KEY | 3 (100.0%) | 3 (100%) | 0  
fake_instance_id | 3 (100.0%) | 3 (100%) | 0  
</details>   
