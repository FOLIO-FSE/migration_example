# Bibliographic records transformation report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-02-16T21:50:23.502490+00:00   
Time Finished: | 2023-02-16T21:50:40.959307+00:00   
Elapsed time: | 0:00:17.456817   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 6 things</summary>     
   
Measure | Count   
--- | ---:   
Inventory records written to disk | 4   
Records in file before parsing | 4   
Records successfully decoded from MARC21 | 4   
SRS records written to disk | 4   
Unique ID:s written to legacy map | 4   
</details>   
   
## Record status (leader pos 5)    
Library action: **All values that are not a, c, d, n or p will be set to c. If this is not what you want, you need to correct these values in your system. **<br/>An overview of the Record statuses (Leader position 5) present in your source data.    Pay attention to the number of occurrences of the value 'd'. These d's are expressing that they are deleted, and the records might not work as expected in FOLIO. Consider marking them as suppressed in your current system and export them as a separate batch in order to have them suppressed in FOLIO. Allowed values according to the MARC standard are a,c,d,n,p    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
n | 4   
</details>   
   
## Trivia    
    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Total number of Tags processed | 20   
</details>   
   
## Holdings type mapping    
    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Condition in rules hit | 4   
x -> Monograph -> Monograph (03c9c400-b9e3-4a07-ac0e-05ab470233ed | 4   
</details>   
   
## Callnumber type mapping    
Call number types in MFHDs are mapped from 852, Indicator 1 according to a certain scheme. (LOC documentation)[https://www.loc.gov/marc/holdings/hd852.html]    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Mapped from Indicator 1 0 -> Library of Congress classification | 4   
</details>   
   
## Location mapping    
These are the results for the mapping between legacy locations and your new FOLIO location structure    
<details><summary>Click to expand all 7 things</summary>     
   
Measure | Count   
--- | ---:   
'cd' (CeeDee) -> CD ROM Carousel | 1   
'infoOff' (InOFF) -> Info Office | 1   
'jnlDesk' (migration) -> Migration Fallback | 1   
'maps' (MAPZ) -> Maps closet | 1   
Fallback mapping: jnlDesk->migration | 1   
Set 852 to FOLIO location code | 4   
</details>   
   
## HRID and 001/035 handling    
There are two ways of handling HRIDs. The default behaviour is to take the current 001 and move that to a new 035. This will also emerge as an Identifier on the Inventory Instances. The 001 and Instance HRID will be generated from the HRID settings in FOLIO. The second option is to maintain the 001s in the records, and also add this as the Instance HRID    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Took HRID from 001 | 4   
</details>   
   
## Suppression    
What records got assigned what suppression setting in the records.    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Suppressed from discovery = False | 4   
</details>   
   
## MARC21 validation issues found in records    
    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
008 lenght invalid. 'xxxxxxxx' was stripped out | 1   
</details>   

## Mapped FOLIO fields
<details><summary>Click to expand field report</summary>     

FOLIO Field | Mapped | Unmapped  
--- | --- | ---:  
_version | 0 (0%) | 4 (100%) 
acquisitionFormat | 0 (0%) | 4 (100%) 
acquisitionMethod | 0 (0%) | 4 (100%) 
administrativeNotes | 4 (100%) | 0 (0%) 
bareHoldingsItems | 0 (0%) | 4 (100%) 
callNumber | 4 (100%) | 0 (0%) 
callNumberPrefix | 0 (0%) | 4 (100%) 
callNumberSuffix | 0 (0%) | 4 (100%) 
callNumberTypeId | 4 (100%) | 0 (0%) 
copyNumber | 0 (0%) | 4 (100%) 
digitizationPolicy | 0 (0%) | 4 (100%) 
discoverySuppress | 4 (100%) | 0 (0%) 
effectiveLocationId | 0 (0%) | 4 (100%) 
electronicAccess | 0 (0%) | 4 (100%) 
formerIds | 4 (100%) | 0 (0%) 
holdingsInstance | 0 (0%) | 4 (100%) 
holdingsItems | 0 (0%) | 4 (100%) 
holdingsStatements | 0 (0%) | 4 (100%) 
holdingsStatementsForIndexes | 0 (0%) | 4 (100%) 
holdingsStatementsForSupplements | 0 (0%) | 4 (100%) 
holdingsTypeId | 4 (100%) | 0 (0%) 
hrid | 4 (100%) | 0 (0%) 
id | 4 (100%) | 0 (0%) 
illPolicy | 0 (0%) | 4 (100%) 
illPolicyId | 0 (0%) | 4 (100%) 
instanceId | 4 (100%) | 0 (0%) 
metadata | 4 (100%) | 0 (0%) 
metadata.createdByUserId | 4 (100%) | 0 (0%) 
metadata.createdDate | 4 (100%) | 0 (0%) 
metadata.updatedByUserId | 4 (100%) | 0 (0%) 
metadata.updatedDate | 4 (100%) | 0 (0%) 
notes | 0 (0%) | 4 (100%) 
numberOfItems | 0 (0%) | 4 (100%) 
permanentLocation | 0 (0%) | 4 (100%) 
permanentLocationId | 4 (100%) | 0 (0%) 
receiptStatus | 0 (0%) | 4 (100%) 
receivingHistory | 0 (0%) | 4 (100%) 
retentionPolicy | 0 (0%) | 4 (100%) 
shelvingTitle | 0 (0%) | 4 (100%) 
sourceId | 4 (100%) | 0 (0%) 
statisticalCodeIds | 0 (0%) | 4 (100%) 
tags | 0 (0%) | 4 (100%) 
temporaryLocationId | 0 (0%) | 4 (100%) 
</details>   

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>     

Legacy Field | Present | Mapped | Unmapped  
--- | --- | --- | ---:  
001 | 4 (100.0%) | 4 (100%) | 0  
004 | 4 (100.0%) | 0 (0%) | 4  
005 | 4 (100.0%) | 0 (0%) | 4  
008 | 4 (100.0%) | 0 (0%) | 4  
852 | 4 (100.0%) | 4 (100%) | 0  
</details>   
