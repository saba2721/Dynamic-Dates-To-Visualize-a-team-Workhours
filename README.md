# Dynamic-Dates-To-Visualize-a-team-Workhours
https://public.tableau.com/app/profile/saba.naaz/viz/DynamicDatestoVisualizeaTeamWorkHours/Dashboard1?publish=yes

This visualization shows the number of hours that one team had spent working on different projects.

The heatmap changes based on the date range selected by the user. If they select a smaller date range, the heatmap shows you the number of hours worked by Day. However, if the user wants to “zoom out” and look at a larger date range then the display will show them the aggregate hours by Weeks or Months.

What if the user isn’t happy with the Default view? Well, we gave them the ability to override it and select their own Date Level.

Requirements
Dashboard Size: 1200 x 800px
2 sheets
Create a heatmap to show the number of hours/minutes worked per person in a specified Date Level (Days/Weeks/Months)
Allow users to filter the dates by a specific Date Range
Make the Date Level dynamic so that users can select from:
 Default, based on Date Range selected:
– For a Date Range less than 28 days aggregate by Days
– For a Date Range less than 90 days aggregate by Weeks
– Otherwise aggregate by Months
 Days
Weeks
Months
Filter by Project
Format the Date Labels
Format the Time to display as Hours + Minutes, e.g.: 185 should display as 3h 05
Create a bar chart for the Total Hours per person (within the selected date range)
Sort both charts by Total Hours in descending order.
