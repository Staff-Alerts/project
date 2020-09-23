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


## Data cleaning and matching

### Staff contacts

* Remove inactive accounts
* Remove non-EA accounts
* Remove landline numbers (not beginning +447)
* Remove short or long numbers (more or less than 12 characters in length)