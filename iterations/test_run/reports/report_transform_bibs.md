# Bibliographic records transformation report
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings

Measure | Value
--- | ---:
Time Started: | 2025-05-29T19:24:40.839059+00:00
Time Finished: | 2025-05-29T19:24:46.850664+00:00
Elapsed time: | 0:00:06.011605
## 

<details><summary>Click to expand all 5 things</summary>

Measure | Count
--- | ---:
Instances HRID starting number | 1
Inventory records written to disk | 26
Records in file before parsing | 26
Records successfully decoded from MARC21 | 26
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

## Mapped contributor name types
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Name type values. The library should review the total number for each value against what they would expect to see mapped.
<details><summary>Click to expand all 3 things</summary>

Measure | Count
--- | ---:
100 -> Personal name | 25
700 -> Personal name | 1
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

## Contributor type mapping
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Contributor type values. The library should review the total number for each value against what they would expect to see mapped.
<details><summary>Click to expand all 3 things</summary>

Measure | Count
--- | ---:
Contributor type code "Author" found for $4 "aut" (aut)) | 22
Contributor type code "Editor" found for $4 "edt" (edt)) | 1
</details>

## Instance format ids handling (337 + 338))

<details><summary>Click to expand all 3 things</summary>

Measure | Count
--- | ---:
338$b is missing. Will try parse from 337$a and 338$a | 10
Successful match  - nc->unmediated -- volume | 3
</details>

## Resource Type Mapping (336)
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Instance type values. The library should review the total number for each value against what they would expect to see mapped.
<details><summary>Click to expand all 2 things</summary>

Measure | Count
--- | ---:
336$b text mapped from txt | 3
</details>

## Mapped FOLIO fields
<details><summary>Click to expand field report</summary>

FOLIO Field | Mapped | Unmapped
---|---|---
_version | 0 (0%) | 26 (100%) 
administrativeNotes | 26 (100%) | 0 (0%) 
alternativeTitles | 0 (0%) | 26 (100%) 
catalogedDate | 0 (0%) | 26 (100%) 
classifications | 0 (0%) | 26 (100%) 
contributors | 26 (100%) | 0 (0%) 
contributors.contributorNameTypeId | 26 (100%) | 0 (0%) 
contributors.contributorTypeId | 23 (88%) | 3 (12%) 
contributors.name | 26 (100%) | 0 (0%) 
contributors.primary | 25 (96%) | 1 (4%) 
dates | 0 (0%) | 26 (100%) 
discoverySuppress | 26 (100%) | 0 (0%) 
editions | 0 (0%) | 26 (100%) 
electronicAccess | 0 (0%) | 26 (100%) 
holdingsRecords2 | 0 (0%) | 26 (100%) 
hrid | 26 (100%) | 0 (0%) 
id | 26 (100%) | 0 (0%) 
identifiers | 0 (0%) | 26 (100%) 
indexTitle | 26 (100%) | 0 (0%) 
instanceFormatIds | 26 (100%) | 0 (0%) 
instanceFormats | 0 (0%) | 26 (100%) 
instanceTypeId | 26 (100%) | 0 (0%) 
languages | 26 (100%) | 0 (0%) 
matchKey | 0 (0%) | 26 (100%) 
metadata | 0 (0%) | 26 (100%) 
modeOfIssuanceId | 26 (100%) | 0 (0%) 
natureOfContentTermIds | 0 (0%) | 26 (100%) 
notes | 0 (0%) | 26 (100%) 
physicalDescriptions | 0 (0%) | 26 (100%) 
previouslyHeld | 0 (0%) | 26 (100%) 
publication | 0 (0%) | 26 (100%) 
publicationFrequency | 0 (0%) | 26 (100%) 
publicationPeriod | 0 (0%) | 26 (100%) 
publicationRange | 0 (0%) | 26 (100%) 
series | 0 (0%) | 26 (100%) 
source | 26 (100%) | 0 (0%) 
sourceRecordFormat | 0 (0%) | 26 (100%) 
staffSuppress | 26 (100%) | 0 (0%) 
statisticalCodeIds | 0 (0%) | 26 (100%) 
statusId | 0 (0%) | 26 (100%) 
statusUpdatedDate | 0 (0%) | 26 (100%) 
subjects | 0 (0%) | 26 (100%) 
tags | 0 (0%) | 26 (100%) 
title | 26 (100%) | 0 (0%) 
</details>

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>

Legacy Field|Present|Mapped|Unmapped
---|---|---|---
</details>
