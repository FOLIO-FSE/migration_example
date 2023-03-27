# Bibliographic records transformation report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-03-27T09:05:07.748803+00:00   
Time Finished: | 2023-03-27T09:05:52.856467+00:00   
Elapsed time: | 0:00:45.107664   
   
##     
    
<details><summary>Click to expand all 6 things</summary>     
   
Measure | Count   
--- | ---:   
Instances HRID starting number | 1   
Inventory records written to disk | 26   
Records in file before parsing | 26   
Records successfully decoded from MARC21 | 26   
SRS records written to disk | 26   
Unique ID:s written to legacy map | 26   
</details>   
   
## HRID and 001/035 handling    
There are two ways of handling HRIDs. The default behaviour is to take the current 001 and move that to a new 035. This will also emerge as an Identifier on the Inventory Instances. The 001 and Instance HRID will be generated from the HRID settings in FOLIO. The second option is to maintain the 001s in the records, and also add this as the Instance HRID    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Took HRID from 001 | 26   
</details>   
   
## Record status (leader pos 5)    
Library action: **All values that are not a, c, d, n or p will be set to c. If this is not what you want, you need to correct these values in your system. **<br/>An overview of the Record statuses (Leader position 5) present in your source data.    Pay attention to the number of occurrences of the value 'd'. These d's are expressing that they are deleted, and the records might not work as expected in FOLIO. Consider marking them as suppressed in your current system and export them as a separate batch in order to have them suppressed in FOLIO. Allowed values according to the MARC standard are a,c,d,n,p    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Original value: c | 10   
Original value: n | 16   
</details>   
   
## Trivia    
    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Total number of Tags processed | 1,267   
</details>   
   
## Mapped identifier types    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Identifier type values. The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 7 things</summary>     
   
Measure | Count   
--- | ---:   
020 -> ISBN | 8   
020 -> Invalid ISBN | 2   
024 -> ISMN | 31   
024 -> Other standard identifier | 31   
024 -> UPC | 31   
035 -> System control number | 8   
</details>   
   
## Authorization sources and related information    
    
<details><summary>Click to expand all 27 things</summary>     
   
Measure | Count   
--- | ---:   
$0 base uri or source code: SwePub | 30   
$0 base uri or source code: Swepub:kth | 39   
$0 base uri or source code: https://id.kb.se | 36   
$0 base uri or source code: https://libris.kb.se | 21   
Source of heading or term: 22 | 1   
Source of heading or term: 23/swe | 7   
Source of heading or term: DOI | 9   
Source of heading or term: doi | 2   
Source of heading or term: hsv | 8   
Source of heading or term: hsv//eng | 15   
Source of heading or term: hsv//swe | 15   
Source of heading or term: kssb | 3   
Source of heading or term: kssb/5 | 1   
Source of heading or term: kssb/8 | 8   
Source of heading or term: lcsh | 4   
Source of heading or term: librisxl | 71   
Source of heading or term: marcgt | 1   
Source of heading or term: rdacarrier | 13   
Source of heading or term: rdacontent | 3   
Source of heading or term: rdamedia | 3   
Source of heading or term: sao | 45   
Source of heading or term: saogf | 2   
Source of heading or term: swepub-contenttype | 10   
Source of heading or term: swepub-publicationtype | 10   
Source of heading or term: uri | 2   
Source of heading or term: urn | 18   
</details>   
   
## Mapped classification types    
    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Dewey | 8   
</details>   
   
## Mapped contributor name types    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Name type values. The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
100 -> Personal name | 25   
700 -> Personal name | 53   
710 -> Corporate name | 18   
</details>   
   
## Mapped note types    
Library action: **REVIEW** <br/>The created FOLIO records contain the following Note type values.  <br/>The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 7 things</summary>     
   
Measure | Count   
--- | ---:   
500 (General note) -> General note | 21   
502 (Dissertation note) -> Dissertation note | 5   
506 (Restrictions on Access note) -> Restrictions on Access note | 2   
520 (Summary) -> Summary | 14   
541 (Immediate Source of Acquisition note) -> Immediate Source of Acquisition note | 1   
546 (Language note) -> Language note | 3   
</details>   
   
## Matched Modes of issuance code    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Mode of issuace values. The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
single unit -- 9d18a02f-5897-4c31-9106-c9abb5c7ae8b | 26   
</details>   
   
## Language codes in records    
A breakdown of language codes occuring in the records. Purely informational.    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
eng | 18   
swe | 11   
</details>   
   
## Suppression    
What records got assigned what suppression setting in the records.    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Staff suppressed = False  | 26   
Suppressed from discovery = False | 26   
</details>   
   
## Holdings generation from bibs    
Some libraries have Holdings/MFHD information baked into their bib records. The following breakdown gives an idea on the occurrence of 852/866 combinations    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Records with both 852s and at least one 86X | 11   
</details>   
   
## Mapped publisher role from Indicator2    
Publication Role, taken from the code in Ind2    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
264 ind2 1->Publication | 23   
264 ind2 3->Manufacture | 4   
264 ind2 4->Copyright notice date | 1   
</details>   
   
## Mapped electronic access relationships types    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Electronic access relationship type values. The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
No information provided | 20   
Related resource | 5   
Resource | 12   
</details>   
   
## Contributor type mapping    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Contributor type values. The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 5 things</summary>     
   
Measure | Count   
--- | ---:   
Contributor type code Author found for $4 "aut" (aut)) | 71   
Contributor type code Editor found for $4 "edt" (edt)) | 3   
Contributor type code Originator found for $4 "org" (org)) | 10   
Contributor type code Publisher found for $4 "pbl" (pbl)) | 8   
</details>   
   
## Instance format ids handling (337 + 338))    
    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
338$b is missing. Will try parse from 337$a and 338$a | 10   
Successful match  - "nc"->unmediated -- volume | 3   
Successful match  - nc->unmediated -- volume | 3   
</details>   
   
## Resource Type Mapping (336)    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Instance type values. The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
336$b text mapped from txt | 3   
</details>   
   
## Set note to staff only via indicator    
    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
541 indicator1:   (1 is public, all other values are Staff only) | 1   
</details>   

## Mapped FOLIO fields
<details><summary>Click to expand field report</summary>     

FOLIO Field | Mapped | Unmapped  
--- | --- | ---:  
_version | 0 (0%) | 26 (100%) 
administrativeNotes | 26 (100%) | 0 (0%) 
alternativeTitles | 0 (0%) | 26 (100%) 
catalogedDate | 0 (0%) | 26 (100%) 
classifications | 8 (31%) | 18 (69%) 
classifications.classificationNumber | 8 (31%) | 18 (69%) 
classifications.classificationTypeId | 8 (31%) | 18 (69%) 
contributors | 26 (100%) | 0 (0%) 
contributors.contributorNameTypeId | 26 (100%) | 0 (0%) 
contributors.contributorTypeId | 26 (100%) | 0 (0%) 
contributors.contributorTypeText | 23 (88%) | 3 (12%) 
contributors.name | 26 (100%) | 0 (0%) 
contributors.primary | 25 (96%) | 1 (4%) 
discoverySuppress | 26 (100%) | 0 (0%) 
editions | 0 (0%) | 26 (100%) 
electronicAccess | 18 (69%) | 8 (31%) 
electronicAccess.linkText | 10 (38%) | 16 (62%) 
electronicAccess.publicNote | 6 (23%) | 20 (77%) 
electronicAccess.relationshipId | 18 (69%) | 8 (31%) 
electronicAccess.uri | 18 (69%) | 8 (31%) 
holdingsRecords2 | 0 (0%) | 26 (100%) 
hrid | 26 (100%) | 0 (0%) 
id | 26 (100%) | 0 (0%) 
identifiers | 21 (81%) | 5 (19%) 
identifiers.identifierTypeId | 21 (81%) | 5 (19%) 
identifiers.value | 21 (81%) | 5 (19%) 
indexTitle | 26 (100%) | 0 (0%) 
instanceFormatIds | 26 (100%) | 0 (0%) 
instanceFormats | 0 (0%) | 26 (100%) 
instanceTypeId | 26 (100%) | 0 (0%) 
languages | 26 (100%) | 0 (0%) 
matchKey | 0 (0%) | 26 (100%) 
metadata | 26 (100%) | 0 (0%) 
metadata.createdByUserId | 26 (100%) | 0 (0%) 
metadata.createdDate | 26 (100%) | 0 (0%) 
metadata.updatedByUserId | 26 (100%) | 0 (0%) 
metadata.updatedDate | 26 (100%) | 0 (0%) 
modeOfIssuanceId | 26 (100%) | 0 (0%) 
natureOfContentTermIds | 0 (0%) | 26 (100%) 
notes | 22 (85%) | 4 (15%) 
notes.instanceNoteTypeId | 22 (85%) | 4 (15%) 
notes.note | 22 (85%) | 4 (15%) 
notes.staffOnly | 1 (4%) | 25 (96%) 
physicalDescriptions | 11 (42%) | 15 (58%) 
previouslyHeld | 0 (0%) | 26 (100%) 
publication | 25 (96%) | 1 (4%) 
publication.dateOfPublication | 25 (96%) | 1 (4%) 
publication.place | 11 (42%) | 15 (58%) 
publication.publisher | 18 (69%) | 8 (31%) 
publication.role | 23 (88%) | 3 (12%) 
publicationFrequency | 0 (0%) | 26 (100%) 
publicationPeriod | 0 (0%) | 26 (100%) 
publicationRange | 0 (0%) | 26 (100%) 
series | 5 (19%) | 21 (81%) 
source | 26 (100%) | 0 (0%) 
sourceRecordFormat | 0 (0%) | 26 (100%) 
staffSuppress | 26 (100%) | 0 (0%) 
statisticalCodeIds | 0 (0%) | 26 (100%) 
statusId | 0 (0%) | 26 (100%) 
statusUpdatedDate | 0 (0%) | 26 (100%) 
subjects | 23 (88%) | 3 (12%) 
tags | 0 (0%) | 26 (100%) 
title | 26 (100%) | 0 (0%) 
</details>   

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>     

Legacy Field | Present | Mapped | Unmapped  
--- | --- | --- | ---:  
001 | 26 (100.0%) | 26 (100%) | 0  
003 | 26 (100.0%) | 0 (0%) | 26  
005 | 16 (61.5%) | 0 (0%) | 16  
007 | 5 (19.2%) | 0 (0%) | 5  
008 | 26 (100.0%) | 26 (100%) | 0  
020 | 9 (34.6%) | 9 (35%) | 0  
024 | 31 (119.2%) | 31 (119%) | 0  
035 | 10 (38.5%) | 10 (38%) | 0  
040 | 26 (100.0%) | 0 (0%) | 26  
041 | 26 (100.0%) | 26 (100%) | 0  
042 | 17 (65.4%) | 0 (0%) | 17  
072 | 20 (76.9%) | 0 (0%) | 20  
082 | 8 (30.8%) | 8 (31%) | 0  
084 | 12 (46.2%) | 0 (0%) | 12  
100 | 25 (96.2%) | 25 (96%) | 0  
245 | 26 (100.0%) | 26 (100%) | 0  
260 | 2 (7.7%) | 2 (8%) | 0  
264 | 28 (107.7%) | 28 (108%) | 0  
300 | 11 (42.3%) | 11 (42%) | 0  
336 | 3 (11.5%) | 3 (12%) | 0  
337 | 3 (11.5%) | 0 (0%) | 3  
338 | 13 (50.0%) | 13 (50%) | 0  
440 | 2 (7.7%) | 0 (0%) | 2  
490 | 5 (19.2%) | 0 (0%) | 5  
500 | 21 (80.8%) | 21 (81%) | 0  
502 | 5 (19.2%) | 5 (19%) | 0  
506 | 2 (7.7%) | 2 (8%) | 0  
520 | 14 (53.8%) | 14 (54%) | 0  
541 | 1 (3.8%) | 1 (4%) | 0  
546 | 3 (11.5%) | 3 (12%) | 0  
599 | 2 (7.7%) | 0 (0%) | 2  
610 | 1 (3.8%) | 1 (4%) | 0  
648 | 3 (11.5%) | 3 (12%) | 0  
650 | 103 (396.2%) | 103 (396%) | 0  
651 | 7 (26.9%) | 7 (27%) | 0  
653 | 65 (250.0%) | 0 (0%) | 65  
655 | 3 (11.5%) | 3 (12%) | 0  
700 | 53 (203.8%) | 53 (204%) | 0  
710 | 18 (69.2%) | 18 (69%) | 0  
772 | 2 (7.7%) | 0 (0%) | 2  
773 | 14 (53.8%) | 0 (0%) | 14  
776 | 4 (15.4%) | 0 (0%) | 4  
830 | 5 (19.2%) | 5 (19%) | 0  
841 | 66 (253.8%) | 0 (0%) | 66  
852 | 70 (269.2%) | 0 (0%) | 70  
856 | 37 (142.3%) | 37 (142%) | 0  
887 | 71 (273.1%) | 0 (0%) | 71  
900 | 1 (3.8%) | 0 (0%) | 1  
910 | 31 (119.2%) | 0 (0%) | 31  
948 | 6 (23.1%) | 0 (0%) | 6  
949 | 1 (3.8%) | 0 (0%) | 1  
950 | 267 (1026.9%) | 0 (0%) | 267  
951 | 1 (3.8%) | 0 (0%) | 1  
955 | 11 (42.3%) | 0 (0%) | 11  
976 | 3 (11.5%) | 0 (0%) | 3  
</details>   
