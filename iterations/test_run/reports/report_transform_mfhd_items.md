# Item transformation report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-03-27T09:32:35.497658+00:00   
Time Finished: | 2023-03-27T09:32:44.493416+00:00   
Elapsed time: | 0:00:08.995758   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 7 things</summary>     
   
Measure | Count   
--- | ---:   
Empty rows in items_linked_to_mfhds.csv | 0   
Number of Legacy items in file_name='items_linked_to_mfhds.csv' suppressed=False staff_suppressed=False service_point_id='' | 6   
Number of files processed | 1   
Number of legacy items in total | 6   
Number of records written to disk | 6   
Total rows in items_linked_to_mfhds.csv | 6   
</details>   
   
## Default values added    
The values below was added to all records from the value field in the mapping file instead of coming from the source records    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
5a15e0f8-2802-4cbf-a4de-8f0dedd3ed3a added to notes[0].itemNoteTypeId | 6   
False added to notes[0].staffOnly | 6   
</details>   
   
## Unmapped properties    
    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
notes[0].staffOnly | 6   
</details>   
   
## Status mapping    
    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
'' -> Available | 6   
</details>   
   
## Mapped Material Types    
    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
33 -> sound recording | 1   
42 -> video recording | 5   
</details>   
   
## Permanent Loan type mapping    
    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
33 -> Reading room | 1   
42 -> Can circulate | 5   
</details>   

## Mapped FOLIO fields
<details><summary>Click to expand field report</summary>     

FOLIO Field | Mapped | Unmapped  
--- | --- | ---:  
_version | 0 (0%) | 2 (100%) 
accessionNumber | 0 (0%) | 2 (100%) 
administrativeNotes | 0 (0%) | 2 (100%) 
barcode | 6 (300%) | 0 (0%) 
chronology | 6 (300%) | 0 (0%) 
circulationNotes | 0 (0%) | 2 (100%) 
copyNumber | 6 (300%) | 0 (0%) 
descriptionOfPieces | 6 (300%) | 0 (0%) 
discoverySuppress | 0 (0%) | 2 (100%) 
effectiveCallNumberComponents | 0 (0%) | 2 (100%) 
effectiveLocationId | 0 (0%) | 2 (100%) 
effectiveShelvingOrder | 0 (0%) | 2 (100%) 
electronicAccess | 0 (0%) | 2 (100%) 
enumeration | 6 (300%) | 0 (0%) 
formerIds | 6 (300%) | 0 (0%) 
holdingsRecord2 | 0 (0%) | 2 (100%) 
holdingsRecordId | 6 (300%) | 0 (0%) 
hrid | 6 (300%) | 0 (0%) 
id | 6 (300%) | 0 (0%) 
inTransitDestinationServicePointId | 0 (0%) | 2 (100%) 
itemDamagedStatusDate | 0 (0%) | 2 (100%) 
itemDamagedStatusId | 0 (0%) | 2 (100%) 
itemIdentifier | 0 (0%) | 2 (100%) 
itemLevelCallNumber | 1 (50%) | 1 (50%) 
itemLevelCallNumberPrefix | 0 (0%) | 2 (100%) 
itemLevelCallNumberSuffix | 0 (0%) | 2 (100%) 
itemLevelCallNumberTypeId | 0 (0%) | 2 (100%) 
lastCheckIn | 0 (0%) | 2 (100%) 
materialType | 0 (0%) | 2 (100%) 
materialTypeId | 6 (300%) | 0 (0%) 
metadata | 6 (300%) | 0 (0%) 
metadata.createdByUserId | 6 (300%) | 0 (0%) 
metadata.createdDate | 6 (300%) | 0 (0%) 
metadata.updatedByUserId | 6 (300%) | 0 (0%) 
metadata.updatedDate | 6 (300%) | 0 (0%) 
missingPieces | 0 (0%) | 2 (100%) 
missingPiecesDate | 0 (0%) | 2 (100%) 
notes | 6 (300%) | 0 (0%) 
notes.itemNoteTypeId | 6 (300%) | 0 (0%) 
notes.note | 6 (300%) | 0 (0%) 
numberOfMissingPieces | 0 (0%) | 2 (100%) 
numberOfPieces | 6 (300%) | 0 (0%) 
permanentLoanTypeId | 6 (300%) | 0 (0%) 
permanentLocation | 0 (0%) | 2 (100%) 
permanentLocationId | 0 (0%) | 2 (100%) 
purchaseOrderLineIdentifier | 0 (0%) | 2 (100%) 
statisticalCodeIds | 0 (0%) | 2 (100%) 
status | 6 (300%) | 0 (0%) 
status.date | 6 (300%) | 0 (0%) 
status.name | 6 (300%) | 0 (0%) 
tags | 0 (0%) | 2 (100%) 
temporaryLoanTypeId | 0 (0%) | 2 (100%) 
temporaryLocation | 0 (0%) | 2 (100%) 
temporaryLocationId | 0 (0%) | 2 (100%) 
volume | 0 (0%) | 2 (100%) 
yearCaption | 6 (300%) | 0 (0%) 
</details>   

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>     

Legacy Field | Present | Mapped | Unmapped  
--- | --- | --- | ---:  
CHRON | 6 (300.0%) | 6 (300%) | 0  
COPY_NUMBER | 6 (300.0%) | 6 (300%) | 0  
ITEM_BARCODE | 6 (300.0%) | 6 (300%) | 0  
ITEM_ENUM | 6 (300.0%) | 6 (300%) | 0  
ITEM_ID | 12 (600.0%) | 12 (600%) | 0  
ITEM_LEVEL_CALL_NUMBER | 1 (50.0%) | 1 (50%) | 0  
ITEM_TYPE_ID | 12 (600.0%) | 12 (600%) | 0  
MFHD_ID | 12 (600.0%) | 12 (600%) | 0  
PIECES | 12 (600.0%) | 12 (600%) | 0  
YEAR | 6 (300.0%) | 6 (300%) | 0  
</details>   
