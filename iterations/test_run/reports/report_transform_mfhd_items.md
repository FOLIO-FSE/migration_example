# Item transformation report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-02-16T21:51:18.947921+00:00   
Time Finished: | 2023-02-16T21:51:37.302508+00:00   
Elapsed time: | 0:00:18.354587   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 7 things</summary>     
   
Measure | Count   
--- | ---:   
Empty rows in items_linked_to_mfhds.csv | 0   
Number of Legacy items in file_name='items_linked_to_mfhds.csv' suppressed=False staff_suppressed=False service_point_id='' | 3   
Number of files processed | 1   
Number of legacy items in total | 3   
Number of records written to disk | 3   
Total rows in items_linked_to_mfhds.csv | 3   
</details>   
   
## Default values added    
The values below was added to all records from the value field in the mapping file instead of coming from the source records    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
5a15e0f8-2802-4cbf-a4de-8f0dedd3ed3a added to notes[0].itemNoteTypeId | 3   
False added to notes[0].staffOnly | 3   
</details>   
   
## Status mapping    
    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
'' -> Available | 3   
</details>   
   
## Mapped Material Types    
    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
33 -> sound recording | 1   
42 -> video recording | 2   
</details>   
   
## Permanent Loan type mapping    
    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
33 -> Reading room | 1   
42 -> Can circulate | 2   
</details>   

## Mapped FOLIO fields
<details><summary>Click to expand field report</summary>     

FOLIO Field | Mapped | Unmapped  
--- | --- | ---:  
_version | 0 (0%) | 3 (100%) 
accessionNumber | 0 (0%) | 3 (100%) 
administrativeNotes | 0 (0%) | 3 (100%) 
barcode | 3 (100%) | 0 (0%) 
chronology | 3 (100%) | 0 (0%) 
circulationNotes | 0 (0%) | 3 (100%) 
copyNumber | 3 (100%) | 0 (0%) 
descriptionOfPieces | 3 (100%) | 0 (0%) 
discoverySuppress | 0 (0%) | 3 (100%) 
effectiveCallNumberComponents | 0 (0%) | 3 (100%) 
effectiveLocationId | 0 (0%) | 3 (100%) 
effectiveShelvingOrder | 0 (0%) | 3 (100%) 
electronicAccess | 0 (0%) | 3 (100%) 
enumeration | 3 (100%) | 0 (0%) 
formerIds | 3 (100%) | 0 (0%) 
holdingsRecord2 | 0 (0%) | 3 (100%) 
holdingsRecordId | 3 (100%) | 0 (0%) 
hrid | 3 (100%) | 0 (0%) 
id | 3 (100%) | 0 (0%) 
inTransitDestinationServicePointId | 0 (0%) | 3 (100%) 
itemDamagedStatusDate | 0 (0%) | 3 (100%) 
itemDamagedStatusId | 0 (0%) | 3 (100%) 
itemIdentifier | 0 (0%) | 3 (100%) 
itemLevelCallNumber | 1 (33%) | 2 (67%) 
itemLevelCallNumberPrefix | 0 (0%) | 3 (100%) 
itemLevelCallNumberSuffix | 0 (0%) | 3 (100%) 
itemLevelCallNumberTypeId | 0 (0%) | 3 (100%) 
lastCheckIn | 0 (0%) | 3 (100%) 
materialType | 0 (0%) | 3 (100%) 
materialTypeId | 3 (100%) | 0 (0%) 
metadata | 3 (100%) | 0 (0%) 
metadata.createdByUserId | 3 (100%) | 0 (0%) 
metadata.createdDate | 3 (100%) | 0 (0%) 
metadata.updatedByUserId | 3 (100%) | 0 (0%) 
metadata.updatedDate | 3 (100%) | 0 (0%) 
missingPieces | 0 (0%) | 3 (100%) 
missingPiecesDate | 0 (0%) | 3 (100%) 
notes | 3 (100%) | 0 (0%) 
notes.itemNoteTypeId | 3 (100%) | 0 (0%) 
notes.note | 3 (100%) | 0 (0%) 
numberOfMissingPieces | 0 (0%) | 3 (100%) 
numberOfPieces | 3 (100%) | 0 (0%) 
permanentLoanTypeId | 3 (100%) | 0 (0%) 
permanentLocation | 0 (0%) | 3 (100%) 
permanentLocationId | 0 (0%) | 3 (100%) 
purchaseOrderLineIdentifier | 0 (0%) | 3 (100%) 
statisticalCodeIds | 0 (0%) | 3 (100%) 
status | 3 (100%) | 0 (0%) 
status.date | 3 (100%) | 0 (0%) 
status.name | 3 (100%) | 0 (0%) 
tags | 0 (0%) | 3 (100%) 
temporaryLoanTypeId | 0 (0%) | 3 (100%) 
temporaryLocation | 0 (0%) | 3 (100%) 
temporaryLocationId | 0 (0%) | 3 (100%) 
volume | 0 (0%) | 3 (100%) 
yearCaption | 3 (100%) | 0 (0%) 
</details>   

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>     

Legacy Field | Present | Mapped | Unmapped  
--- | --- | --- | ---:  
CHRON | 3 (100.0%) | 3 (100%) | 0  
COPY_NUMBER | 3 (100.0%) | 3 (100%) | 0  
ITEM_BARCODE | 3 (100.0%) | 3 (100%) | 0  
ITEM_ENUM | 3 (100.0%) | 3 (100%) | 0  
ITEM_ID | 6 (200.0%) | 6 (200%) | 0  
ITEM_LEVEL_CALL_NUMBER | 1 (33.3%) | 1 (33%) | 0  
ITEM_TYPE_ID | 6 (200.0%) | 6 (200%) | 0  
MFHD_ID | 6 (200.0%) | 6 (200%) | 0  
PIECES | 6 (200.0%) | 6 (200%) | 0  
YEAR | 3 (100.0%) | 3 (100%) | 0  
</details>   
