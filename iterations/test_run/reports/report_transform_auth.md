# Authority records transformation report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-01-31T08:05:56.530234+00:00   
Time Finished: | 2023-01-31T08:07:05.384889+00:00   
Elapsed time: | 0:01:08.854655   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 6 things</summary>     
   
Measure | Count   
--- | ---:   
Inventory records written to disk | 55,420   
Records in file before parsing | 55,420   
Records successfully decoded from MARC21 | 55,420   
SRS records written to disk | 55,420   
Unique ID:s written to legacy map | 55,420   
</details>   
   
## Leader manipulation    
    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Set leader 10 (Indicator count) from   to 2 | 47,778   
Set leader 10 (Subfield code count) from   to 2 | 47,778   
</details>   
   
## HRID and 001/035 handling    
There are two ways of handling HRIDs. The default behaviour is to take the current 001 and move that to a new 035. This will also emerge as an Identifier on the Inventory Instances. The 001 and Instance HRID will be generated from the HRID settings in FOLIO. The second option is to maintain the 001s in the records, and also add this as the Instance HRID    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Added 035 from 001 | 55,420   
Values in 003: Empty | 55,420   
</details>   
   
## Trivia    
    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Total number of Tags processed | 734,620   
</details>   
   
## Mapped identifier types    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Identifier type values. The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
010 -> LCCN | 6,663   
024 -> Other standard identifier | 48,186   
System control number | 72,314   
</details>   
   
## Authorization sources and related information    
    
<details><summary>Click to expand all 89 things</summary>     
   
Measure | Count   
--- | ---:   
$0 base uri or source code: CaOONL | 5   
$0 base uri or source code: DCL | 13   
$0 base uri or source code: DELC | 1   
$0 base uri or source code: DLC | 1,851   
$0 base uri or source code: DLOC | 1   
$0 base uri or source code: DNB | 1   
$0 base uri or source code: FLC | 2   
$0 base uri or source code: LC | 2   
$0 base uri or source code: gmgpc | 31   
$0 base uri or source code: https://libris.kb.se | 16   
$0 base uri or source code: n | 1   
Source of heading or term: /kssb/7 | 2   
Source of heading or term: 22 | 63   
Source of heading or term: 22/swe | 2   
Source of heading or term: 23 | 7   
Source of heading or term: 23(swe | 1   
Source of heading or term: 23/ | 1   
Source of heading or term: 23/sw | 2   
Source of heading or term: 23/swe | 3,664   
Source of heading or term: 237swe | 1   
Source of heading or term: 23swe | 1   
Source of heading or term: AuCNLKIN | 284   
Source of heading or term: Birthday | 1   
Source of heading or term: Birthday.se | 1   
Source of heading or term: LCSH | 2   
Source of heading or term: VIAF | 1   
Source of heading or term: aat | 8   
Source of heading or term: agrovoc | 1   
Source of heading or term: aiatsiss | 1   
Source of heading or term: baf | 1   
Source of heading or term: bnfcg | 2   
Source of heading or term: bound | 2   
Source of heading or term: cerl | 2   
Source of heading or term: dot | 1   
Source of heading or term: edtf | 1,108   
Source of heading or term: eidr | 1   
Source of heading or term: eurovocen | 1   
Source of heading or term: fast | 3   
Source of heading or term: full | 4   
Source of heading or term: geonames | 20   
Source of heading or term: geonet | 8   
Source of heading or term: gettytgn | 1   
Source of heading or term: gmgpc | 452   
Source of heading or term: gnd | 2   
Source of heading or term: gnis | 1   
Source of heading or term: iconauth | 1   
Source of heading or term: idref | 2   
Source of heading or term: isni | 35,523   
Source of heading or term: iso5218 | 1   
Source of heading or term: itoamc | 6   
Source of heading or term: ksb/8 | 1   
Source of heading or term: kssb | 3   
Source of heading or term: kssb/ | 1   
Source of heading or term: kssb/7 | 5,550   
Source of heading or term: kssb/8 | 4,416   
Source of heading or term: kssb77 | 1   
Source of heading or term: kssb8 | 10   
Source of heading or term: kssk/8 | 1   
Source of heading or term: ksssb/8 | 1   
Source of heading or term: lach | 1   
Source of heading or term: lcdgt | 420   
Source of heading or term: lcgft | 483   
Source of heading or term: lcmpt | 178   
Source of heading or term: lcsh | 2,431   
Source of heading or term: libaus | 1   
Source of heading or term: librisxl | 47,778   
Source of heading or term: local | 3   
Source of heading or term: lsch | 1   
Source of heading or term: mesh | 4   
Source of heading or term: mlati | 132   
Source of heading or term: musicb | 2   
Source of heading or term: naf | 1,533   
Source of heading or term: opensm | 1   
Source of heading or term: orcid | 12   
Source of heading or term: other | 15   
Source of heading or term: pe | 1   
Source of heading or term: rdacontent | 2   
Source of heading or term: rid | 1   
Source of heading or term: sao | 192   
Source of heading or term: saogf | 1   
Source of heading or term: scopus | 4   
Source of heading or term: stw | 1   
Source of heading or term: thesoz | 1   
Source of heading or term: uri | 38   
Source of heading or term: viaf | 12,565   
Source of heading or term: wfbcia | 1   
Source of heading or term: wikidata | 15   
Source of heading or term: wikiped | 1   
</details>   
   
## Mapped note types    
Library action: **REVIEW** <br/>The created FOLIO instances contain the following Note type values.  <br/>The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Nonpublic general note | 11,023   
</details>   

## Mapped FOLIO fields
<details><summary>Click to expand field report</summary>     

FOLIO Field | Mapped | Unmapped  
--- | --- | ---:  
_version | 0 (0%) | 55,420 (100%) 
corporateName | 1,837 (3%) | 53,583 (97%) 
corporateNameTitle | 1,837 (3%) | 53,583 (97%) 
genreTerm | 2,150 (4%) | 53,270 (96%) 
geographicName | 725 (1%) | 54,695 (99%) 
id | 55,420 (100%) | 0 (0%) 
identifiers | 55,420 (100%) | 0 (0%) 
identifiers.identifierTypeId | 55,420 (100%) | 0 (0%) 
identifiers.value | 55,420 (100%) | 0 (0%) 
meetingName | 13 (0%) | 55,407 (100%) 
meetingNameTitle | 13 (0%) | 55,407 (100%) 
metadata | 55,420 (100%) | 0 (0%) 
metadata.createdByUserId | 55,420 (100%) | 0 (0%) 
metadata.createdDate | 55,420 (100%) | 0 (0%) 
metadata.updatedByUserId | 55,420 (100%) | 0 (0%) 
metadata.updatedDate | 55,420 (100%) | 0 (0%) 
naturalId | 0 (0%) | 55,420 (100%) 
notes | 10,659 (19%) | 44,761 (81%) 
notes.note | 10,659 (19%) | 44,761 (81%) 
notes.noteTypeId | 10,659 (19%) | 44,761 (81%) 
personalName | 44,471 (80%) | 10,949 (20%) 
personalNameTitle | 44,471 (80%) | 10,949 (20%) 
saftCorporateName | 397 (1%) | 55,023 (99%) 
saftCorporateNameTitle | 397 (1%) | 55,023 (99%) 
saftGenreTerm | 957 (2%) | 54,463 (98%) 
saftGeographicName | 101 (0%) | 55,319 (100%) 
saftMeetingName | 2 (0%) | 55,418 (100%) 
saftMeetingNameTitle | 2 (0%) | 55,418 (100%) 
saftPersonalName | 722 (1%) | 54,698 (99%) 
saftPersonalNameTitle | 722 (1%) | 54,698 (99%) 
saftTopicalTerm | 4,792 (9%) | 50,628 (91%) 
saftUniformTitle | 24 (0%) | 55,396 (100%) 
sftCorporateName | 1,715 (3%) | 53,705 (97%) 
sftCorporateNameTitle | 1,715 (3%) | 53,705 (97%) 
sftGenreTerm | 854 (2%) | 54,566 (98%) 
sftGeographicName | 397 (1%) | 55,023 (99%) 
sftMeetingName | 12 (0%) | 55,408 (100%) 
sftMeetingNameTitle | 12 (0%) | 55,408 (100%) 
sftPersonalName | 23,908 (43%) | 31,512 (57%) 
sftPersonalNameTitle | 23,908 (43%) | 31,512 (57%) 
sftTopicalTerm | 2,239 (4%) | 53,181 (96%) 
sftUniformTitle | 132 (0%) | 55,288 (100%) 
source | 55,420 (100%) | 0 (0%) 
sourceFileId | 0 (0%) | 55,420 (100%) 
subjectHeadings | 0 (0%) | 55,420 (100%) 
topicalTerm | 5,817 (10%) | 49,603 (90%) 
uniformTitle | 222 (0%) | 55,198 (100%) 
</details>   

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>     

Legacy Field | Present | Mapped | Unmapped  
--- | --- | --- | ---:  
001 | 55,420 (100.0%) | 55,420 (100%) | 0  
005 | 55,420 (100.0%) | 0 (0%) | 55,420  
008 | 55,420 (100.0%) | 55,420 (100%) | 0  
010 | 6,256 (11.3%) | 6,256 (11%) | 0  
016 | 307 (0.6%) | 0 (0%) | 307  
022 | 8 (0.0%) | 0 (0%) | 8  
024 | 48,186 (86.9%) | 48,186 (87%) | 0  
031 | 2 (0.0%) | 0 (0%) | 2  
034 | 48 (0.1%) | 0 (0%) | 48  
035 | 72,314 (130.5%) | 72,314 (130%) | 0  
040 | 55,418 (100.0%) | 0 (0%) | 55,418  
042 | 8,314 (15.0%) | 0 (0%) | 8,314  
043 | 34,012 (61.4%) | 0 (0%) | 34,012  
045 | 38 (0.1%) | 0 (0%) | 38  
046 | 5,589 (10.1%) | 0 (0%) | 5,589  
050 | 22 (0.0%) | 0 (0%) | 22  
053 | 416 (0.8%) | 0 (0%) | 416  
065 | 10,025 (18.1%) | 0 (0%) | 10,025  
072 | 2 (0.0%) | 0 (0%) | 2  
083 | 3,776 (6.8%) | 0 (0%) | 3,776  
100 | 44,471 (80.2%) | 44,471 (80%) | 0  
110 | 1,837 (3.3%) | 1,837 (3%) | 0  
111 | 13 (0.0%) | 13 (0%) | 0  
130 | 222 (0.4%) | 222 (0%) | 0  
148 | 124 (0.2%) | 0 (0%) | 124  
150 | 5,817 (10.5%) | 5,817 (10%) | 0  
151 | 725 (1.3%) | 725 (1%) | 0  
155 | 2,150 (3.9%) | 2,150 (4%) | 0  
180 | 42 (0.1%) | 0 (0%) | 42  
260 | 1 (0.0%) | 0 (0%) | 1  
336 | 1 (0.0%) | 0 (0%) | 1  
360 | 11 (0.0%) | 0 (0%) | 11  
368 | 362 (0.7%) | 0 (0%) | 362  
370 | 3,253 (5.9%) | 0 (0%) | 3,253  
371 | 158 (0.3%) | 0 (0%) | 158  
372 | 1,383 (2.5%) | 0 (0%) | 1,383  
373 | 1,652 (3.0%) | 0 (0%) | 1,652  
374 | 3,041 (5.5%) | 0 (0%) | 3,041  
375 | 1,781 (3.2%) | 0 (0%) | 1,781  
376 | 38 (0.1%) | 0 (0%) | 38  
377 | 1,740 (3.1%) | 0 (0%) | 1,740  
378 | 467 (0.8%) | 0 (0%) | 467  
380 | 509 (0.9%) | 0 (0%) | 509  
381 | 50 (0.1%) | 0 (0%) | 50  
382 | 210 (0.4%) | 0 (0%) | 210  
383 | 257 (0.5%) | 0 (0%) | 257  
384 | 85 (0.2%) | 0 (0%) | 85  
386 | 1 (0.0%) | 0 (0%) | 1  
400 | 53,688 (96.9%) | 53,688 (97%) | 0  
410 | 4,022 (7.3%) | 4,022 (7%) | 0  
411 | 31 (0.1%) | 31 (0%) | 0  
430 | 401 (0.7%) | 401 (1%) | 0  
448 | 139 (0.3%) | 0 (0%) | 139  
450 | 4,125 (7.4%) | 4,125 (7%) | 0  
451 | 1,014 (1.8%) | 1,014 (2%) | 0  
455 | 1,561 (2.8%) | 1,561 (3%) | 0  
480 | 28 (0.1%) | 0 (0%) | 28  
500 | 905 (1.6%) | 905 (2%) | 0  
510 | 525 (0.9%) | 525 (1%) | 0  
511 | 2 (0.0%) | 2 (0%) | 0  
530 | 52 (0.1%) | 52 (0%) | 0  
550 | 14,050 (25.4%) | 14,050 (25%) | 0  
551 | 146 (0.3%) | 146 (0%) | 0  
555 | 2,412 (4.4%) | 2,412 (4%) | 0  
580 | 15 (0.0%) | 0 (0%) | 15  
640 | 4 (0.0%) | 0 (0%) | 4  
641 | 6 (0.0%) | 0 (0%) | 6  
642 | 95 (0.2%) | 0 (0%) | 95  
643 | 172 (0.3%) | 0 (0%) | 172  
644 | 157 (0.3%) | 0 (0%) | 157  
645 | 163 (0.3%) | 0 (0%) | 163  
646 | 159 (0.3%) | 0 (0%) | 159  
663 | 66 (0.1%) | 0 (0%) | 66  
665 | 129 (0.2%) | 0 (0%) | 129  
667 | 10,854 (19.6%) | 10,854 (20%) | 0  
670 | 76,103 (137.3%) | 0 (0%) | 76,103  
672 | 1 (0.0%) | 0 (0%) | 1  
675 | 400 (0.7%) | 0 (0%) | 400  
678 | 27,229 (49.1%) | 0 (0%) | 27,229  
680 | 95 (0.2%) | 0 (0%) | 95  
681 | 19 (0.0%) | 0 (0%) | 19  
688 | 1,010 (1.8%) | 0 (0%) | 1,010  
700 | 1,493 (2.7%) | 0 (0%) | 1,493  
710 | 1 (0.0%) | 0 (0%) | 1  
730 | 23 (0.0%) | 0 (0%) | 23  
750 | 2,911 (5.3%) | 0 (0%) | 2,911  
751 | 458 (0.8%) | 0 (0%) | 458  
755 | 673 (1.2%) | 0 (0%) | 673  
781 | 68 (0.1%) | 0 (0%) | 68  
856 | 43 (0.1%) | 0 (0%) | 43  
887 | 47,778 (86.2%) | 0 (0%) | 47,778  
</details>   
