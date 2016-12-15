Reports
=======

|image|\ The reports module of rebus:list allows you to query the
database directly so you can gather statistical data about your lists
and users.

15.1 Creating a report

rebus:list accepts PostgreSQL for new reports.

|image|

+-----------+----------------------------------------------------------------------------------------------+
| |image|   | The link is available from the about rebus:list page which is linked to from the main menu   |
+===========+==============================================================================================+
+-----------+----------------------------------------------------------------------------------------------+

|image|\ To create a new report click the Create a New Report button and
you will be presented with the report builder box.

You must enter a name for the report and then enter the query before you
can save your report

|image|

rebus:list will not allow you to save an invalid query as a report and
will instead give an error that provides information about its location.

+-----------+-----------+
| |image|   | |image|   |
+===========+===========+
+-----------+-----------+

Clicking save will save your report ready for it to be run. We
understand that not all customers will wish to create sql reports from
scratch so we have created a report library that contains canned reports
for some of the more commonly needed data. Reports from the library can
be cut and pasted directly into the report builder:

https://ptfs-europe.github.io/rebus-list/reports/

If you are using a report from the library please pay attention to the
attached notes as they will keep you informed of any extra variables
that need to be entered and what format they need to be in.

|image|\ In this example report from the report library you can see that
the report will ask you to enter dates as separate variables. It also
specifies the format they should be in.

When you run this report within rebus:list you will see the screen below
that allows you to add the required parameters for the report to run.

|image|

Note. It is important to get the format of the data for these parameters
right as you are running a direct query on the database and the use of
variables will allow you to enter a malformed query. Doing this will
make the report fail.

15.2 Working with Reports

Once a report has been created it becomes available on the Reports list
and it is from here that you will work with it.

-  Report Name - The name provided in the report builder

-  Creator - The username of the report creator

-  Last Updated - The date that the report was last edited

-  Last Run - The date the report was last run

-  Runs pending - This shows requested reports that haven’t yet
   completed

-  Enabled - This shows the reports current running status

-  Actions - The options that allow you to work with the reports

When you have written a lot of reports you can use the search function
to find the relevant one. You can enter a search term and filter by
Enabled / Disabled or Both.

|image|

Once you have found the right report use the action buttons to work with
it

+-----------+--------------------------------------------------------------------------------------------------------------------------------------------+
| |image|   | This button allows you to clone an existing report. This means you can retain the existing report whilst creating another based upon it.   |
+===========+============================================================================================================================================+
| |image|   | This button opens the report builder for editing the selected report.                                                                      |
+-----------+--------------------------------------------------------------------------------------------------------------------------------------------+
| |image|   | This button disables the report - the report is not deleted but can then be filtered out as a report that is not currently used.           |
+-----------+--------------------------------------------------------------------------------------------------------------------------------------------+
+-----------+--------------------------------------------------------------------------------------------------------------------------------------------+

+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| |image|   | This button allows you to schedule a report - currently this will enable you to delay the running of the report until a specified system time. This is to allow you to avoid adverse effects on system performance. (See 5.1)   |
+===========+=================================================================================================================================================================================================================================+
| |image|   | This is the run button clicking this button will make the report run asap.                                                                                                                                                      |
+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| |image|   | Once a report has been run the eye button will appear which will allow you to view the report.                                                                                                                                  |
+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

15.3 Viewing a Report

|image|\ To view a report click on the eye button next to it on the
reports page. Results view will open.

From here you can view the results for any run of the specific report
you have chosen

-  |image|\ Use the drop down to choose a specific result set

-  |image|\ See the query that has been run

-  |image|\ See a table of the results returned

-  |image|\ Search from within the results

It’s also possible to generate and download the reports output as a csv
format flat file which can then be edited in numerous other
applications. To do this first click the ‘Generate CSV From Results’
then click the provided link to download the file.

+-----------+-----------+
| |image|   | |image|   |
+===========+===========+
+-----------+-----------+

|image|
