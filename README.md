# PowerBI_DimDate
An M Query to create a repeatable Date dimension table.

Rather than creating a table from scratch, this offers a quick way to create a date table for you to create relationships with.

## Installation
- Open up Power BI and on the Home Tab, click Transform data.<br>
![Transform Data](https://raw.githubusercontent.com/mathewrtaylor/PowerBI_DimDate/screenshots/DimDate_1.png?raw=true "Icon to Transform Data.")<br>
- On the Home Tab click on the words New Source, then Blank Query.<br>
![Blank Query](https://raw.githubusercontent.com/mathewrtaylor/PowerBI_DimDate/screenshots/DimDate_2.png?raw=true "Steps to create a new Blank Query.")<br>
- A New Query entitled Query1 will be created.  On the Home Tab, click Advanced Editor.<br>
![Advanced Editor](https://raw.githubusercontent.com/mathewrtaylor/PowerBI_DimDate/screenshots/DimDate_3.png?raw=true "Advanced Editor.")<br>
- In the new Window that opens up, select all and replace with the contents of the text file.<br>
![Query Contents](https://raw.githubusercontent.com/mathewrtaylor/PowerBI_DimDate/screenshots/DimDate_4.png?raw=true "Paste Contents of the Query in here!")<br>
- Select Done.<br>
![Done](https://raw.githubusercontent.com/mathewrtaylor/PowerBI_DimDate/screenshots/DimDate_5.png?raw=true "Finish off the Query Editor.")<br><br>
Congratulations, the hard work is done!!

## Usage
- Click on Query1, and select your earliest date you wish to have in the table in the StartDate box by either inputting directly as MM/DD/YYYY or by clicking the calendar button.<br>
- Select your latest date you wish to have in the table in the EndDate box by either inputting directly as MM/DD/YYYY or by clicking the calendar button.<br>
![Select Dates](https://raw.githubusercontent.com/mathewrtaylor/PowerBI_DimDate/screenshots/DimDate_6.png?raw=true "Select your earliest (StartDate) and latest (EndDate) dates.")<br>
- Once you are happy with the earliest (StartDate) and latest (EndDate) dates in your table, click the Invoke button.<br>
![Invoke Function](https://raw.githubusercontent.com/mathewrtaylor/PowerBI_DimDate/screenshots/DimDate_7.png?raw=true "It's go time, press Invoke!")<br>
- This will create a new Table currently entitled Invoked Function.  Remember to right-click and rename to whatever naming convention is appropriate to your naming convention.  Congratulations!!<br>
![Rename Function](https://raw.githubusercontent.com/mathewrtaylor/PowerBI_DimDate/screenshots/DimDate_8.png?raw=true "Remember to rename this to something like DimDate, or what makes sense to you!")<br><br>

This will create a table ready to go with the appropriate labels and data types selected!<br>
![Output](https://raw.githubusercontent.com/mathewrtaylor/PowerBI_DimDate/screenshots/DimDate_9.png?raw=true "Here is an example of what the output will look like once done.")<br>

## Credits
Direct inspiration from Devin Knight's query at: https://devinknightsql.com/2015/06/16/creating-a-date-dimension-with-power-query/

## License
[MIT](https://choosealicense.com/licenses/mit/)
