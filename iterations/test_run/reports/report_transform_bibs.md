# Bibliographic records transformation report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-01-31T12:49:57.408611+00:00   
Time Finished: | 2023-01-31T12:50:18.570354+00:00   
Elapsed time: | 0:00:21.161743   
   
##     
    
<details><summary>Click to expand all 6 things</summary>     
   
Measure | Count   
--- | ---:   
Instances HRID starting number | 1   
Inventory records written to disk | 14   
Records in file before parsing | 14   
Records successfully decoded from MARC21 | 14   
SRS records written to disk | 14   
Unique ID:s written to legacy map | 14   
</details>   
   
## HRID and 001/035 handling    
There are two ways of handling HRIDs. The default behaviour is to take the current 001 and move that to a new 035. This will also emerge as an Identifier on the Inventory Instances. The 001 and Instance HRID will be generated from the HRID settings in FOLIO. The second option is to maintain the 001s in the records, and also add this as the Instance HRID    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Took HRID from 001 | 14   
</details>   
   
## Record status (leader pos 5)    
Library action: **All values that are not a, c, d, n or p will be set to c. If this is not what you want, you need to correct these values in your system. **<br/>An overview of the Record statuses (Leader position 5) present in your source data.    Pay attention to the number of occurrences of the value 'd'. These d's are expressing that they are deleted, and the records might not work as expected in FOLIO. Consider marking them as suppressed in your current system and export them as a separate batch in order to have them suppressed in FOLIO. Allowed values according to the MARC standard are a,c,d,n,p    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Original value: c | 4   
Original value: n | 10   
</details>   
   
## Trivia    
    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Total number of Tags processed | 435   
</details>   
   
## Mapped identifier types    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Identifier type values. The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 6 things</summary>     
   
Measure | Count   
--- | ---:   
020 -> ISBN | 3   
024 -> ISMN | 19   
024 -> Other standard identifier | 19   
024 -> UPC | 19   
035 -> System control number | 2   
</details>   
   
## Authorization sources and related information    
    
<details><summary>Click to expand all 22 things</summary>     
   
Measure | Count   
--- | ---:   
$0 base uri or source code: SwePub | 30   
$0 base uri or source code: Swepub:kth | 39   
$0 base uri or source code: https://id.kb.se | 1   
$0 base uri or source code: https://libris.kb.se | 1   
Source of heading or term: 22 | 1   
Source of heading or term: 23/swe | 1   
Source of heading or term: DOI | 9   
Source of heading or term: hsv//eng | 15   
Source of heading or term: hsv//swe | 15   
Source of heading or term: kssb | 3   
Source of heading or term: kssb/5 | 1   
Source of heading or term: kssb/8 | 2   
Source of heading or term: librisxl | 6   
Source of heading or term: rdacarrier | 11   
Source of heading or term: rdacontent | 1   
Source of heading or term: rdamedia | 1   
Source of heading or term: sao | 1   
Source of heading or term: saogf | 1   
Source of heading or term: swepub-contenttype | 10   
Source of heading or term: swepub-publicationtype | 10   
Source of heading or term: urn | 10   
</details>   
   
## Mapped classification types    
    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Dewey | 2   
</details>   
   
## Mapped contributor name types    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Name type values. The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
100 -> Personal name | 14   
700 -> Personal name | 42   
710 -> Corporate name | 10   
</details>   
   
## Mapped note types    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Note type values.  <br/>The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 5 things</summary>     
   
Measure | Count   
--- | ---:   
500 (General note) -> General note | 12   
502 (Dissertation note) -> Dissertation note | 1   
520 (Summary) -> Summary | 10   
546 (Language note) -> Language note | 1   
</details>   
   
## Matched Modes of issuance code    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Mode of issuace values. The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
single unit -- 9d18a02f-5897-4c31-9106-c9abb5c7ae8b | 14   
</details>   
   
## Language codes in records    
A breakdown of language codes occuring in the records. Purely informational.    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
eng | 12   
swe | 3   
</details>   
   
## Suppression    
What records got assigned what suppression setting in the records.    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Staff suppressed = False  | 14   
Suppressed from discovery = False | 14   
</details>   
   
## Holdings generation from bibs    
Some libraries have Holdings/MFHD information baked into their bib records. The following breakdown gives an idea on the occurrence of 852/866 combinations    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Records with both 852s and at least one 86X | 2   
</details>   
   
## Mapped publisher role from Indicator2    
Publication Role, taken from the code in Ind2    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
264 ind2 1->Publication | 12   
264 ind2 3->Manufacture | 2   
</details>   
   
## Mapped electronic access relationships types    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Electronic access relationship type values. The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
No information provided | 20   
Related resource | 1   
</details>   
   
## Contributor type mapping    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Contributor type values. The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Contributor type code Author found for $4 "aut" (aut)) | 54   
Contributor type code Originator found for $4 "org" (org)) | 10   
</details>   
   
## Instance format ids handling (337 + 338))    
    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
338$b is missing. Will try parse from 337$a and 338$a | 10   
Successful match  - "nc"->unmediated -- volume | 1   
Successful match  - nc->unmediated -- volume | 1   
</details>   
   
## Resource Type Mapping (336)    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Instance type values. The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
336$b text mapped from txt | 1   
</details>   

## Mapped FOLIO fields
<details><summary>Click to expand field report</summary>     

FOLIO Field | Mapped | Unmapped  
--- | --- | ---:  
_version | 0 (0%) | 14 (100%) 
administrativeNotes | 14 (100%) | 0 (0%) 
alternativeTitles | 0 (0%) | 14 (100%) 
catalogedDate | 0 (0%) | 14 (100%) 
classifications | 2 (14%) | 12 (86%) 
classifications.classificationNumber | 2 (14%) | 12 (86%) 
classifications.classificationTypeId | 2 (14%) | 12 (86%) 
contributors | 14 (100%) | 0 (0%) 
contributors.contributorNameTypeId | 14 (100%) | 0 (0%) 
contributors.contributorTypeId | 14 (100%) | 0 (0%) 
contributors.contributorTypeText | 14 (100%) | 0 (0%) 
contributors.name | 14 (100%) | 0 (0%) 
contributors.primary | 14 (100%) | 0 (0%) 
discoverySuppress | 14 (100%) | 0 (0%) 
editions | 0 (0%) | 14 (100%) 
electronicAccess | 11 (79%) | 3 (21%) 
electronicAccess.linkText | 10 (71%) | 4 (29%) 
electronicAccess.relationshipId | 11 (79%) | 3 (21%) 
electronicAccess.uri | 11 (79%) | 3 (21%) 
holdingsRecords2 | 0 (0%) | 14 (100%) 
hrid | 14 (100%) | 0 (0%) 
id | 14 (100%) | 0 (0%) 
identifiers | 14 (100%) | 0 (0%) 
identifiers.identifierTypeId | 13 (93%) | 1 (7%) 
identifiers.value | 13 (93%) | 1 (7%) 
indexTitle | 14 (100%) | 0 (0%) 
instanceFormatIds | 14 (100%) | 0 (0%) 
instanceFormats | 0 (0%) | 14 (100%) 
instanceTypeId | 14 (100%) | 0 (0%) 
languages | 14 (100%) | 0 (0%) 
matchKey | 0 (0%) | 14 (100%) 
metadata | 14 (100%) | 0 (0%) 
metadata.createdByUserId | 14 (100%) | 0 (0%) 
metadata.createdDate | 14 (100%) | 0 (0%) 
metadata.updatedByUserId | 14 (100%) | 0 (0%) 
metadata.updatedDate | 14 (100%) | 0 (0%) 
modeOfIssuanceId | 14 (100%) | 0 (0%) 
natureOfContentTermIds | 0 (0%) | 14 (100%) 
notes | 13 (93%) | 1 (7%) 
notes.instanceNoteTypeId | 13 (93%) | 1 (7%) 
notes.note | 13 (93%) | 1 (7%) 
physicalDescriptions | 4 (29%) | 10 (71%) 
previouslyHeld | 0 (0%) | 14 (100%) 
publication | 13 (93%) | 1 (7%) 
publication.dateOfPublication | 13 (93%) | 1 (7%) 
publication.place | 4 (29%) | 10 (71%) 
publication.publisher | 9 (64%) | 5 (36%) 
publication.role | 12 (86%) | 2 (14%) 
publicationFrequency | 0 (0%) | 14 (100%) 
publicationPeriod | 0 (0%) | 14 (100%) 
publicationRange | 0 (0%) | 14 (100%) 
series | 1 (7%) | 13 (93%) 
source | 14 (100%) | 0 (0%) 
sourceRecordFormat | 0 (0%) | 14 (100%) 
staffSuppress | 14 (100%) | 0 (0%) 
statisticalCodeIds | 0 (0%) | 14 (100%) 
statusId | 0 (0%) | 14 (100%) 
statusUpdatedDate | 0 (0%) | 14 (100%) 
subjects | 11 (79%) | 3 (21%) 
tags | 0 (0%) | 14 (100%) 
title | 14 (100%) | 0 (0%) 
</details>   

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>     

Legacy Field | Present | Mapped | Unmapped  
--- | --- | --- | ---:  
001 | 14 (100.0%) | 14 (100%) | 0  
003 | 14 (100.0%) | 0 (0%) | 14  
005 | 4 (28.6%) | 0 (0%) | 4  
008 | 14 (100.0%) | 14 (100%) | 0  
020 | 3 (21.4%) | 3 (21%) | 0  
024 | 19 (135.7%) | 19 (136%) | 0  
035 | 4 (28.6%) | 4 (29%) | 0  
040 | 14 (100.0%) | 0 (0%) | 14  
041 | 14 (100.0%) | 14 (100%) | 0  
042 | 12 (85.7%) | 0 (0%) | 12  
072 | 20 (142.9%) | 0 (0%) | 20  
082 | 2 (14.3%) | 2 (14%) | 0  
084 | 6 (42.9%) | 0 (0%) | 6  
100 | 14 (100.0%) | 14 (100%) | 0  
245 | 14 (100.0%) | 14 (100%) | 0  
260 | 1 (7.1%) | 1 (7%) | 0  
264 | 14 (100.0%) | 14 (100%) | 0  
300 | 4 (28.6%) | 4 (29%) | 0  
336 | 1 (7.1%) | 1 (7%) | 0  
337 | 1 (7.1%) | 0 (0%) | 1  
338 | 11 (78.6%) | 11 (79%) | 0  
440 | 2 (14.3%) | 0 (0%) | 2  
490 | 1 (7.1%) | 0 (0%) | 1  
500 | 12 (85.7%) | 12 (86%) | 0  
502 | 1 (7.1%) | 1 (7%) | 0  
520 | 10 (71.4%) | 10 (71%) | 0  
546 | 1 (7.1%) | 1 (7%) | 0  
599 | 1 (7.1%) | 0 (0%) | 1  
650 | 31 (221.4%) | 31 (221%) | 0  
653 | 53 (378.6%) | 0 (0%) | 53  
655 | 1 (7.1%) | 1 (7%) | 0  
700 | 42 (300.0%) | 42 (300%) | 0  
710 | 10 (71.4%) | 10 (71%) | 0  
773 | 9 (64.3%) | 0 (0%) | 9  
830 | 1 (7.1%) | 1 (7%) | 0  
841 | 11 (78.6%) | 0 (0%) | 11  
852 | 12 (85.7%) | 0 (0%) | 12  
856 | 21 (150.0%) | 21 (150%) | 0  
887 | 6 (42.9%) | 0 (0%) | 6  
900 | 1 (7.1%) | 0 (0%) | 1  
955 | 8 (57.1%) | 0 (0%) | 8  
976 | 1 (7.1%) | 0 (0%) | 1  
</details>   
