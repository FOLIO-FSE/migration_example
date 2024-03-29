# Item transformation report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-03-27T09:38:50.494363+00:00   
Time Finished: | 2023-03-27T09:39:02.377625+00:00   
Elapsed time: | 0:00:11.883262   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 7 things</summary>     
   
Measure | Count   
--- | ---:   
Empty rows in bw_items.tsv | 0   
Number of Legacy items in file_name='bw_items.tsv' suppressed=False staff_suppressed=False service_point_id='' | 10   
Number of files processed | 1   
Number of legacy items in total | 10   
Number of records written to disk | 10   
Total rows in bw_items.tsv | 10   
</details>   
   
## Status mapping    
    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
'' -> Available | 10   
</details>   
   
## Mapped Material Types    
    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
a   -> sound recording | 9   
c   -> video recording | 1   
</details>   
   
## Permanent Loan type mapping    
    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
0 -> Can circulate | 9   
199 -> Reading room | 1   
</details>   

## Mapped FOLIO fields
<details><summary>Click to expand field report</summary>     

FOLIO Field | Mapped | Unmapped  
--- | --- | ---:  
_version | 0 (0%) | 10 (100%) 
accessionNumber | 0 (0%) | 10 (100%) 
administrativeNotes | 0 (0%) | 10 (100%) 
barcode | 10 (100%) | 0 (0%) 
chronology | 0 (0%) | 10 (100%) 
circulationNotes | 0 (0%) | 10 (100%) 
copyNumber | 0 (0%) | 10 (100%) 
descriptionOfPieces | 0 (0%) | 10 (100%) 
discoverySuppress | 0 (0%) | 10 (100%) 
effectiveCallNumberComponents | 0 (0%) | 10 (100%) 
effectiveLocationId | 0 (0%) | 10 (100%) 
effectiveShelvingOrder | 0 (0%) | 10 (100%) 
electronicAccess | 0 (0%) | 10 (100%) 
enumeration | 0 (0%) | 10 (100%) 
formerIds | 10 (100%) | 0 (0%) 
holdingsRecord2 | 0 (0%) | 10 (100%) 
holdingsRecordId | 10 (100%) | 0 (0%) 
hrid | 10 (100%) | 0 (0%) 
id | 10 (100%) | 0 (0%) 
inTransitDestinationServicePointId | 0 (0%) | 10 (100%) 
itemDamagedStatusDate | 0 (0%) | 10 (100%) 
itemDamagedStatusId | 0 (0%) | 10 (100%) 
itemIdentifier | 0 (0%) | 10 (100%) 
itemLevelCallNumber | 0 (0%) | 10 (100%) 
itemLevelCallNumberPrefix | 0 (0%) | 10 (100%) 
itemLevelCallNumberSuffix | 0 (0%) | 10 (100%) 
itemLevelCallNumberTypeId | 0 (0%) | 10 (100%) 
lastCheckIn | 0 (0%) | 10 (100%) 
materialType | 0 (0%) | 10 (100%) 
materialTypeId | 10 (100%) | 0 (0%) 
metadata | 10 (100%) | 0 (0%) 
metadata.createdByUserId | 10 (100%) | 0 (0%) 
metadata.createdDate | 10 (100%) | 0 (0%) 
metadata.updatedByUserId | 10 (100%) | 0 (0%) 
metadata.updatedDate | 10 (100%) | 0 (0%) 
missingPieces | 0 (0%) | 10 (100%) 
missingPiecesDate | 0 (0%) | 10 (100%) 
notes | 0 (0%) | 10 (100%) 
numberOfMissingPieces | 0 (0%) | 10 (100%) 
numberOfPieces | 0 (0%) | 10 (100%) 
permanentLoanTypeId | 10 (100%) | 0 (0%) 
permanentLocation | 0 (0%) | 10 (100%) 
permanentLocationId | 0 (0%) | 10 (100%) 
purchaseOrderLineIdentifier | 0 (0%) | 10 (100%) 
statisticalCodeIds | 0 (0%) | 10 (100%) 
status | 10 (100%) | 0 (0%) 
status.date | 10 (100%) | 0 (0%) 
status.name | 10 (100%) | 0 (0%) 
tags | 0 (0%) | 10 (100%) 
temporaryLoanTypeId | 0 (0%) | 10 (100%) 
temporaryLocation | 0 (0%) | 10 (100%) 
temporaryLocationId | 0 (0%) | 10 (100%) 
volume | 0 (0%) | 10 (100%) 
yearCaption | 0 (0%) | 10 (100%) 
</details>   

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>     

Legacy Field | Present | Mapped | Unmapped  
--- | --- | --- | ---:  
BARCODE(ITEM) | 10 (100.0%) | 10 (100%) | 0  
I TYPE | 10 (100.0%) | 10 (100%) | 0  
MAT TYPE | 10 (100.0%) | 10 (100%) | 0  
RECORD #(BIBLIO) | 10 (100.0%) | 10 (100%) | 0  
RECORD #(ITEM) | 30 (300.0%) | 30 (300%) | 0  
</details>   
