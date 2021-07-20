# Data Discrepancy Issue

This notebook follows a set of steps to determine whether there were content items (articles or books) missing between two data sets.

The process was used for real troubleshooting steps where a customer claimed discrepancy between the data presented in our reports and the data they received from the content provider.

The two files used were "ytd_report.csv" and "compl.csv".

## Steps:
* Import both data sets and confirm record counts. 
* Applied data cleansing to ensure content name integrity (changed content titles to lower case format).
* Performed outer join to match on Content Type.
* Exported results to csv file (records not found).
