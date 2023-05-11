# Ogranization transformation report   
<br/>Data errors preventing records from being migrated are marked **FIX BEFORE MIGRATION**. The library is advised to clean up these errors in the source data.<br/><br/> The sections related to field counts and mapping results are marked **REVIEW**. These do not indicate errors preventing records from being migrated, but may point to data anomalies or in the mappings. The library should review these to make sure that the numbers are what one would expect, knowing the source data. Is this the expected number of serials? Is this the expected number of cartographic materials?
## Timings   
   
Measure | Value   
--- | ---:   
Time Started: | 2023-05-11T11:15:31.626009+00:00   
Time Finished: | 2023-05-11T11:15:48.933279+00:00   
Elapsed time: | 0:00:17.307270   
   
## General statistics    
A list of general counters to outline the transformation as a whole.    
<details><summary>Click to expand all 10 things</summary>     
   
Measure | Count   
--- | ---:   
Number of empty rows in test_organizations.tsv | 0   
Number of files processed | 1   
Number of linked contacts created | 3   
Number of linked interfaceCredential created | 2   
Number of linked interfaces created | 4   
Number of linked notes created | 3   
Number of objects in source data file | 3   
Number of organizations created | 3   
Number of rows in test_organizations.tsv | 3   
</details>   
   
## Organization types    
Reference data mapping for Organization types.    
<details><summary>Click to expand all 3 things</summary>     
   
Measure | Count   
--- | ---:   
Unmapped (Default value was set) -- ast -> Unspecified | 1   
cst -> Consortium | 2   
</details>   
   
## FOLIO default values added    
The below FOLIO default values were added to records that had no mapped value in the source data.    
<details><summary>Click to expand all 68 things</summary>     
   
Measure | Count   
--- | ---:   
 added to accounts[0].accountNo | 1   
 added to accounts[0].accountStatus | 3   
 added to addresses[0].stateRegion | 3   
 added to addresses[0].zipCode | 2   
 added to aliases[0].description | 2   
 added to aliases[0].value | 1   
 added to contacts[0].addresses[0].addressLine1 | 4   
 added to contacts[0].addresses[0].city | 8   
 added to contacts[0].categories[0] | 8   
 added to contacts[0].firstName | 4   
 added to contacts[0].lastName | 4   
 added to contacts[0].notes | 4   
 added to contacts[0].phoneNumbers[0].phoneNumber | 4   
 added to contacts[1].addresses[0].addressLine1 | 6   
 added to contacts[1].addresses[0].city | 9   
 added to contacts[1].firstName | 6   
 added to contacts[1].lastName | 6   
 added to contacts[1].notes | 6   
 added to edi.ediFtp.ftpConnMode | 3   
 added to edi.ediFtp.ftpFormat | 3   
 added to edi.ediFtp.ftpMode | 3   
 added to edi.ediFtp.ftpPort | 3   
 added to edi.ediFtp.invoiceDirectory | 3   
 added to edi.ediFtp.notes | 3   
 added to edi.ediFtp.orderDirectory | 3   
 added to edi.ediFtp.password | 3   
 added to edi.ediFtp.serverAddress | 3   
 added to edi.ediFtp.username | 3   
 added to edi.ediJob.isFriday | 3   
 added to edi.ediJob.isMonday | 3   
 added to edi.ediJob.isSaturday | 3   
 added to edi.ediJob.isSunday | 3   
 added to edi.ediJob.isThursday | 3   
 added to edi.ediJob.isTuesday | 3   
 added to edi.ediJob.isWednesday | 3   
 added to edi.ediJob.notifyAllEdi | 3   
 added to edi.ediJob.notifyErrorOnly | 3   
 added to edi.ediJob.notifyInvoiceOnly | 3   
 added to edi.ediJob.scheduleEdi | 3   
 added to edi.ediJob.schedulingDate | 3   
 added to edi.ediJob.schedulingNotes | 3   
 added to edi.ediJob.sendToEmails | 3   
 added to edi.ediJob.time | 3   
 added to edi.ediNamingConvention | 3   
 added to edi.libEdiCode | 3   
 added to edi.libEdiType | 3   
 added to edi.notes | 3   
 added to edi.prorateFees | 3   
 added to edi.prorateTax | 3   
 added to edi.sendAcctNum | 3   
 added to edi.supportInvoice | 3   
 added to edi.supportOrder | 3   
 added to edi.vendorEdiCode | 3   
 added to edi.vendorEdiType | 3   
 added to emails[0].value | 2   
 added to interfaces[0].deliveryMethod | 4   
 added to interfaces[0].interfaceCredential.password | 2   
 added to interfaces[0].interfaceCredential.username | 2   
 added to interfaces[0].locallyStored | 4   
 added to interfaces[0].notes | 4   
 added to interfaces[0].onlineLocation | 4   
 added to interfaces[0].statisticsFormat | 4   
 added to interfaces[0].statisticsNotes | 4   
 added to interfaces[0].type[0] | 2   
 added to interfaces[1].name | 2   
 added to interfaces[1].uri | 2   
 added to phoneNumbers[0].phoneNumber | 1   
</details>   
   
## Default values from mapping added    
The values below were added to all records from the 'value' field in the mapping file, overriding any mapped values from the source data.    
<details><summary>Click to expand all 10 things</summary>     
   
Measure | Count   
--- | ---:   
Admin added to interfaces[1].type[0] | 3   
Migrated note added to notes[0].title | 3   
True added to addresses[0].isPrimary | 3   
True added to contacts[0].addresses[0].isPrimary | 12   
True added to contacts[0].phoneNumbers[0].isPrimary | 12   
True added to contacts[1].addresses[0].isPrimary | 9   
True added to interfaces[0].available | 6   
f5bba0d2-7732-4687-8311-a2cb0eaa12e5 added to notes[0].typeId | 3   
organizations added to notes[0].domain | 3   
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
<details><summary>Click to expand all 6 things</summary>     
   
Measure | Count   
--- | ---:   
accounts | 2   
contacts | 3   
emails | 2   
interfaces | 2   
phoneNumbers | 1   
</details>   
   
## Mapping details    
    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
Replaced mspt<^>sls in contact_1_categories with e193b0d1-4674-4a9e-818b-375f013d963f<^>604c2c9d-ed3a-46cd-bec4-69926c303b22 | 4   
</details>   
   
## Mapped note types    
Library action: **REVIEW** <br/>The created FOLIO records contain the following Note type values.  <br/>The library should review the total number for each value against what they would expect to see mapped.    
<details><summary>Click to expand all 2 things</summary>     
   
Measure | Count   
--- | ---:   
f5bba0d2-7732-4687-8311-a2cb0eaa12e5 | 3   
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
contacts | 2 (67%) | 1 (33%) 
contacts.addresses | 2 (67%) | 1 (33%) 
contacts.addresses.addressLine1 | 2 (67%) | 1 (33%) 
contacts.addresses.city | 1 (33%) | 2 (67%) 
contacts.addresses.isPrimary | 2 (67%) | 1 (33%) 
contacts.categories | 1 (33%) | 2 (67%) 
contacts.firstName | 2 (67%) | 1 (33%) 
contacts.lastName | 2 (67%) | 1 (33%) 
contacts.notes | 2 (67%) | 1 (33%) 
contacts.phoneNumbers | 2 (67%) | 1 (33%) 
contacts.phoneNumbers.isPrimary | 2 (67%) | 1 (33%) 
contacts.phoneNumbers.phoneNumber | 2 (67%) | 1 (33%) 
description | 0 (0%) | 3 (100%) 
discountPercent | 0 (0%) | 3 (100%) 
edi | 0 (0%) | 3 (100%) 
emails | 1 (33%) | 2 (67%) 
emails.categories | 1 (33%) | 2 (67%) 
emails.value | 1 (33%) | 2 (67%) 
erpCode | 0 (0%) | 3 (100%) 
expectedActivationInterval | 0 (0%) | 3 (100%) 
expectedInvoiceInterval | 0 (0%) | 3 (100%) 
expectedReceiptInterval | 0 (0%) | 3 (100%) 
exportToAccounting | 0 (0%) | 3 (100%) 
governmental | 0 (0%) | 3 (100%) 
id | 3 (100%) | 0 (0%) 
interfaces | 3 (100%) | 0 (0%) 
interfaces.available | 3 (100%) | 0 (0%) 
interfaces.deliveryMethod | 1 (33%) | 2 (67%) 
interfaces.interfaceCredential | 3 (100%) | 0 (0%) 
interfaces.interfaceCredential.interfaceId | 3 (100%) | 0 (0%) 
interfaces.interfaceCredential.password | 2 (67%) | 1 (33%) 
interfaces.interfaceCredential.username | 2 (67%) | 1 (33%) 
interfaces.locallyStored | 1 (33%) | 2 (67%) 
interfaces.name | 3 (100%) | 0 (0%) 
interfaces.notes | 1 (33%) | 2 (67%) 
interfaces.onlineLocation | 1 (33%) | 2 (67%) 
interfaces.statisticsFormat | 1 (33%) | 2 (67%) 
interfaces.statisticsNotes | 1 (33%) | 2 (67%) 
interfaces.type | 2 (67%) | 1 (33%) 
interfaces.uri | 3 (100%) | 0 (0%) 
isVendor | 0 (0%) | 3 (100%) 
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
ACCTNUM | 3 (100.0%) | 3 (100%) | 0  
Active | 3 (100.0%) | 3 (100%) | 0  
Alt name type | 3 (100.0%) | 3 (100%) | 0  
Alternative Names | 3 (100.0%) | 3 (100%) | 0  
EMAIL | 3 (100.0%) | 3 (100%) | 0  
PHONE NUM | 3 (100.0%) | 3 (100%) | 0  
VENNAME | 3 (100.0%) | 3 (100%) | 0  
address_city | 3 (100.0%) | 3 (100%) | 0  
address_line_1 | 3 (100.0%) | 3 (100%) | 0  
address_state | 3 (100.0%) | 3 (100%) | 0  
address_zip | 3 (100.0%) | 3 (100%) | 0  
contact_1_address_city | 24 (800.0%) | 24 (800%) | 0  
contact_1_address_line1 | 12 (400.0%) | 12 (400%) | 0  
contact_1_fname | 12 (400.0%) | 12 (400%) | 0  
contact_1_lname | 12 (400.0%) | 12 (400%) | 0  
contact_1_note | 12 (400.0%) | 12 (400%) | 0  
contact_1_phone | 12 (400.0%) | 12 (400%) | 0  
contact_2_address_city | 18 (600.0%) | 18 (600%) | 0  
contact_2_address_line1 | 9 (300.0%) | 9 (300%) | 0  
contact_2_fname | 9 (300.0%) | 9 (300%) | 0  
contact_2_lname | 9 (300.0%) | 9 (300%) | 0  
contact_2_note | 9 (300.0%) | 9 (300%) | 0  
interface_1_delivery | 6 (200.0%) | 6 (200%) | 0  
interface_1_localLocation | 6 (200.0%) | 6 (200%) | 0  
interface_1_name | 6 (200.0%) | 6 (200%) | 0  
interface_1_notes | 6 (200.0%) | 6 (200%) | 0  
interface_1_onlineLocation | 6 (200.0%) | 6 (200%) | 0  
interface_1_statFormat | 6 (200.0%) | 6 (200%) | 0  
interface_1_statNotes | 6 (200.0%) | 6 (200%) | 0  
interface_1_uri | 6 (200.0%) | 6 (200%) | 0  
interface_2_name | 3 (100.0%) | 3 (100%) | 0  
interface_2_uri | 3 (100.0%) | 3 (100%) | 0  
org_type | 3 (100.0%) | 3 (100%) | 0  
status | 3 (100.0%) | 3 (100%) | 0  
vendor_code | 3 (100.0%) | 3 (100%) | 0  
</details>   
