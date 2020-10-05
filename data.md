# Staff Alerts - Data 

Data standards are an essential tool in good data management. By defining, publishing and using data standards, we can improve consistency in our data, so that it is:

* is easier to join it up
* is easier to analyse
* is easier to re-use
* is more reliable for reporting
* can reduce the cost of changing the format at a later date

## Data sources

| Name                         | Source                  | Notes  | 
| -------------                |------------             |------- |
| Public Facing Area Names     | EA                      | Taken from data standards list |
| Office Names and Codes       | EA                      | Taken from data standards list |
| Staff contacts               | Defra Active Directory  | Taken from data standards list |


## Data standards

| Name                                                                                                                                       | Source          | Notes  | 
| -------------                                                                                                                              |------------     |------- |
| [Date-times and time-stamps](https://www.gov.uk/government/publications/open-standards-for-government/date-times-and-time-stamps-standard) | GDS             |        |
| [Encoding characters](https://www.gov.uk/government/publications/open-standards-for-government/cross-platform-character-encoding-profile)  | GDS             |        |


## Data cleansing

### Staff contacts

* Remove inactive accounts
* Remove non-EA accounts
* Remove landline numbers (not beginning 447)
* Remove short numbers (less than 12 characters in length)
* Remove all non-numeric characters
* Find and clean long numbers with additional "0" i.e. 4407123456789
* Find and clean long numbers with additional "440" i.e. 440447123456789

* Create suppression list of known generic accounts

* Need to also get Defra colleagues details in the following offices:
    * NOBEL HOUSE LONDON
    * TEMPLE QUAY HOUSE BRISTOL 
    * CREWE HSE HORNBEAM HOUSE
    * DEFRA MANLEY HOUSE EXETER
    * READING NORTH GATE HOUSE
    * Worcester CC 
    * Eden Bridge 
    * Lancaster House

## Data matching

### Staff locations

* Create matching table for Active Directory offices to EA Office names list
* Create matching table for EA Office names list to EA Operational Area




## Data flows

* Create a record in the database, tied to the Active Directory UDID, with the data-cleansed string recorded against Staff Mobile
