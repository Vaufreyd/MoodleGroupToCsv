# MoodleGroupToCsv
A local web page with some JavaScript to convert a list of Moodle groups with students to a searchable list for spreadsheet application.
Your data are NOT SENT to an external server, computaiton is done locally on your computer (inside the Web page).

# How to use it
## Step 1: get the list of groups with users from Moodle

Got to the settings of groups in your course. In the global overview of groups, you should see a list of groups, their users and the number of users within each group (the image was captured on a French Moodle):

![Moodle groups](ListOfGroups.jpg)

Copy paste text into the dedicated area of the MooodleGroupToCsv.html local page. Here for instance, from A1 (left top) to 16 (bottom right on last line).

## Step 2: choose to export (or not) the email from student (default=no)

## Step 3: select CSV export style

You can select Flat CSV (default) to get rows containing student, (email, ), group name. Non flat CSV will generate Group name on a single line followed by a list of students in this group (one on each line).

## Step 4: set (or not) the file name to generate

## Step 5: click on the "Generate CSV!" button to get your CSV file

## Step 6: check log for information and errors.

## Step 7: import the CSV file to your favorite spreadsheet application

It is usually as easy as open the ".csv" file. You can use this list using vertical search function to associate users to their group.
