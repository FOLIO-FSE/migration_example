# Holdings transformation report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-01-18T12:01:26.952390+00:00   
Time Finished: | 2023-01-18T12:01:34.326540+00:00   
Elapsed time: | 0:00:07.374150   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 15 things</summary>     
   
Measure | Count   
--- | ---:   
BW Items found tied to previously created BW Holdings | 2   
Bib ids referenced in bound-with items | 18   
Bound-with holdings created | 18   
Bound-with items callnumber identified | 9   
Bound-with items identified by bib id | 9   
Empty rows in bw_items.tsv | 0   
Holdings Records Written to disk | 17   
Number of Legacy items in file | 10   
Number of files processed | 1   
Records matched to Instances | 19   
Total rows in bw_items.tsv | 10   
Unique BW Holdings created from Items | 16   
Unique Holdings created from Items | 1   
Unique ID:s written to legacy map | 29   
</details>   
   
## Bound-with mapping    
    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
Number of bib records referenced in item: 1 | 1   
Number of bib records referenced in item: 2 | 9   
Number of bib-level callnumbers in record: 2 | 9   
</details>   
   
## Location mapping    
These are the results for the mapping between legacy locations and your new FOLIO location structure    
<details><summary>Click to expand all 5 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) --    -> migration | 1   
jnlDesk   -> JOURDESK | 5   
jnlDesk -> JOURDESK | 2   
maps   -> MAPZ | 2   
</details>   
   
## Default values added    
The values below was added to all records from the value field in the mapping file instead of coming from the source records    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
97fbb130-beb4-4eec-84a6-c69768ca3eea added to notes[0].holdingsNoteTypeId | 10   
true added to notes[0].staffOnly | 10   
</details>   

## Mapped FOLIO fields
<details><summary>Click to expand field report</summary>     

FOLIO Field | Mapped | Unmapped  
--- | --- | ---:  
_version | 0 (0%) | 10 (100%) 
acquisitionFormat | 0 (0%) | 10 (100%) 
acquisitionMethod | 0 (0%) | 10 (100%) 
administrativeNotes | 0 (0%) | 10 (100%) 
bareHoldingsItems | 0 (0%) | 10 (100%) 
callNumber | 10 (100%) | 0 (0%) 
callNumberPrefix | 0 (0%) | 10 (100%) 
callNumberSuffix | 0 (0%) | 10 (100%) 
callNumberTypeId | 0 (0%) | 10 (100%) 
copyNumber | 0 (0%) | 10 (100%) 
digitizationPolicy | 0 (0%) | 10 (100%) 
discoverySuppress | 0 (0%) | 10 (100%) 
effectiveLocationId | 0 (0%) | 10 (100%) 
electronicAccess | 0 (0%) | 10 (100%) 
formerIds | 10 (100%) | 0 (0%) 
holdingsInstance | 0 (0%) | 10 (100%) 
holdingsItems | 0 (0%) | 10 (100%) 
holdingsStatements | 0 (0%) | 10 (100%) 
holdingsStatementsForIndexes | 0 (0%) | 10 (100%) 
holdingsStatementsForSupplements | 0 (0%) | 10 (100%) 
holdingsTypeId | 10 (100%) | 0 (0%) 
hrid | 0 (0%) | 10 (100%) 
id | 10 (100%) | 0 (0%) 
illPolicy | 0 (0%) | 10 (100%) 
illPolicyId | 0 (0%) | 10 (100%) 
instanceId | 10 (100%) | 0 (0%) 
metadata | 10 (100%) | 0 (0%) 
metadata.createdByUserId | 10 (100%) | 0 (0%) 
metadata.createdDate | 10 (100%) | 0 (0%) 
metadata.updatedByUserId | 10 (100%) | 0 (0%) 
metadata.updatedDate | 10 (100%) | 0 (0%) 
notes | 10 (100%) | 0 (0%) 
notes.holdingsNoteTypeId | 10 (100%) | 0 (0%) 
notes.note | 10 (100%) | 0 (0%) 
notes.staffOnly | 10 (100%) | 0 (0%) 
numberOfItems | 0 (0%) | 10 (100%) 
permanentLocation | 0 (0%) | 10 (100%) 
permanentLocationId | 10 (100%) | 0 (0%) 
receiptStatus | 0 (0%) | 10 (100%) 
receivingHistory | 0 (0%) | 10 (100%) 
retentionPolicy | 0 (0%) | 10 (100%) 
shelvingTitle | 0 (0%) | 10 (100%) 
sourceId | 10 (100%) | 0 (0%) 
statisticalCodeIds | 0 (0%) | 10 (100%) 
tags | 0 (0%) | 10 (100%) 
temporaryLocationId | 0 (0%) | 10 (100%) 
</details>   

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>     

Legacy Field | Present | Mapped | Unmapped  
--- | --- | --- | ---:  
CALL #(BIBLIO) | 10 (100.0%) | 10 (100%) | 0  
LOCATION | 10 (100.0%) | 10 (100%) | 0  
RECORD #(BIBLIO) | 20 (200.0%) | 20 (200%) | 0  
RECORD #(ITEM) | 10 (100.0%) | 10 (100%) | 0  
</details>   
