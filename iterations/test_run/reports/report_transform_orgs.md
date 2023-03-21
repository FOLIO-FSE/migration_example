# Ogranization transformation report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-03-21T13:22:45.645915+00:00   
Time Finished: | 2023-03-21T13:22:58.603018+00:00   
Elapsed time: | 0:00:12.957103   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 7 things</summary>     
   
Measure | Count   
--- | ---:   
Empty rows in test_organizations.tsv | 0   
Number of files processed | 1   
Number of linked contacts created | 3   
Number of objects in source data file | 3   
Number of organizations created | 3   
Total rows in test_organizations.tsv | 3   
</details>   
   
## Default values added    
The values below was added to all records from the value field in the mapping file instead of coming from the source records    
<details><summary>Click to expand all 7 things</summary>     
   
Measure | Count   
--- | ---:   
From Schema: exportToAccounting -> False | 3   
From Schema: isVendor -> False | 3   
True added to addresses[0].isPrimary | 3   
True added to contacts[0].addresses[0].isPrimary | 12   
True added to contacts[0].phoneNumbers[0].isPrimary | 12   
True added to contacts[1].addresses[0].isPrimary | 9   
</details>   
   
## Organization types    
Reference data mapping for Organization types.    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) -- ast -> General | 1   
cst -> Consortium | 2   
</details>   
   
## Organization contact categories    
Reference data mapping for contacts, addresses, emails, and phones numbers.    
<details><summary>Click to expand all 5 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) --  -> General | 4   
Unmapped (Default value was set) -- spt -> General | 3   
rt -> Returns | 1   
tspt -> Technical Support | 1   
</details>   
   
## Sub-property removed due to missing required fields    
Add the missing required information to the record in your current ILS to ensure that it can be migrated over.    
<details><summary>Click to expand all 4 things</summary>     
   
Measure | Count   
--- | ---:   
accounts | 2   
emails | 2   
phoneNumbers | 1   
</details>   

## Mapped FOLIO fields
<details><summary>Click to expand field report</summary>     

FOLIO Field | Mapped | Unmapped  
--- | --- | ---:  
accessProvider | 0 (0%) | 3 (100%) 
accounts | 0 (0%) | 3 (100%) 
acqUnitIds | 0 (0%) | 3 (100%) 
addresses | 3 (100%) | 0 (0%) 
addresses.addressLine1 | 3 (100%) | 0 (0%) 
addresses.categories | 3 (100%) | 0 (0%) 
addresses.city | 3 (100%) | 0 (0%) 
addresses.isPrimary | 3 (100%) | 0 (0%) 
addresses.zipCode | 1 (33%) | 2 (67%) 
agreements | 0 (0%) | 3 (100%) 
aliases | 2 (67%) | 1 (33%) 
aliases.description | 1 (33%) | 2 (67%) 
aliases.value | 2 (67%) | 1 (33%) 
changelogs | 0 (0%) | 3 (100%) 
claimingInterval | 0 (0%) | 3 (100%) 
code | 3 (100%) | 0 (0%) 
contacts | 3 (100%) | 0 (0%) 
contacts.addresses | 3 (100%) | 0 (0%) 
contacts.addresses.addressLine1 | 2 (67%) | 1 (33%) 
contacts.addresses.city | 1 (33%) | 2 (67%) 
contacts.addresses.isPrimary | 3 (100%) | 0 (0%) 
contacts.firstName | 2 (67%) | 1 (33%) 
contacts.lastName | 2 (67%) | 1 (33%) 
contacts.notes | 2 (67%) | 1 (33%) 
contacts.phoneNumbers | 3 (100%) | 0 (0%) 
contacts.phoneNumbers.isPrimary | 3 (100%) | 0 (0%) 
contacts.phoneNumbers.phoneNumber | 2 (67%) | 1 (33%) 
description | 3 (100%) | 0 (0%) 
discountPercent | 0 (0%) | 3 (100%) 
edi | 0 (0%) | 3 (100%) 
emails | 1 (33%) | 2 (67%) 
emails.categories | 1 (33%) | 2 (67%) 
emails.value | 1 (33%) | 2 (67%) 
erpCode | 0 (0%) | 3 (100%) 
expectedActivationInterval | 0 (0%) | 3 (100%) 
expectedInvoiceInterval | 0 (0%) | 3 (100%) 
expectedReceiptInterval | 0 (0%) | 3 (100%) 
exportToAccounting | 3 (100%) | 0 (0%) 
governmental | 0 (0%) | 3 (100%) 
id | 3 (100%) | 0 (0%) 
interfaces | 0 (0%) | 3 (100%) 
isVendor | 3 (100%) | 0 (0%) 
language | 0 (0%) | 3 (100%) 
liableForVat | 0 (0%) | 3 (100%) 
licensor | 0 (0%) | 3 (100%) 
materialSupplier | 0 (0%) | 3 (100%) 
metadata | 3 (100%) | 0 (0%) 
metadata.createdByUserId | 3 (100%) | 0 (0%) 
metadata.createdDate | 3 (100%) | 0 (0%) 
metadata.updatedByUserId | 3 (100%) | 0 (0%) 
metadata.updatedDate | 3 (100%) | 0 (0%) 
name | 3 (100%) | 0 (0%) 
organizationTypes | 3 (100%) | 0 (0%) 
paymentMethod | 0 (0%) | 3 (100%) 
phoneNumbers | 2 (67%) | 1 (33%) 
phoneNumbers.categories | 2 (67%) | 1 (33%) 
phoneNumbers.phoneNumber | 2 (67%) | 1 (33%) 
renewalActivationInterval | 0 (0%) | 3 (100%) 
sanCode | 0 (0%) | 3 (100%) 
status | 3 (100%) | 0 (0%) 
subscriptionInterval | 0 (0%) | 3 (100%) 
tags | 0 (0%) | 3 (100%) 
taxId | 0 (0%) | 3 (100%) 
taxPercentage | 0 (0%) | 3 (100%) 
urls | 0 (0%) | 3 (100%) 
vendorCurrencies | 0 (0%) | 3 (100%) 
</details>   

## Mapped Legacy fields
<details><summary>Click to expand field report</summary>     

Legacy Field | Present | Mapped | Unmapped  
--- | --- | --- | ---:  
VENNAME | 3 (100.0%) | 3 (100%) | 0  
org_note | 6 (200.0%) | 6 (200%) | 0  
org_type | 3 (100.0%) | 3 (100%) | 0  
status | 3 (100.0%) | 3 (100%) | 0  
vendor_code | 3 (100.0%) | 3 (100%) | 0  
</details>   
