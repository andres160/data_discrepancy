#Data Discrepancy

This notebook follows a set of steps to determine whether there were content items (articles or books) missing between two data sets.
Process was used for a real troubleshooting steps where customer claimed discrepancy between the data presented in our reports and the data they received from the content provider.

The two files used were "ytd_report.csv" and "compl.csv".

#Steps:
Import both data sets and confirm record counts. 
Applied data cleansing to ensure conten name matched (changed to lower case).
Performed outer join to match on Content Type.
Exported results of records not found to csv file.
