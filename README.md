# sara_alert_merge_mine
Mini project to compile Sara Alert end-of-day reports and mine resulting data. 

## Requirements
- python=3.8*
- pandas=1.2*
- openpyxl=3.0*

## Installing
No installation required except prerequisite python modules. 

## Performed operations
- Scan directory for excel files: Y:\Confidential\DCHS\CDE\01_Linelists_Cross Coverage\Novel CoV\SARA\SARA Investigator Assignments\Assignments
    - read directories/subdirectories
        - extract dir name value for timestamp
        - load data from files that contain "EOD" in file name
        - load tabs from excel with the names: ["TOTAL", "Completed_LTFU_Returned_to_Doh"]
    - concat all the "TOTALS" and a .csv file and the "Completed_LTFU_Returned_to_Doh" into another .csv file
    - include a column that contains timestamp from directory that contains that file
        
## Contributors
Alexey Gilman, 10/05/2021