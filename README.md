Simplifying personal task management using R Shiny
================
Joe Omatoi

![](sample_screenshot.png)

### Purpose

This interactive dashboard simplifies personal task management into 2
simple ideas: 1) the optimal order in which tasks should be completed
and 2) the number of hours/day required to complete tasks on time.

### How it works

Under “manage tasks,” tasks can be added to or removed from the
calendar, which displays tasks in 30 minute chunks and orders them by
deadline first and then priority level. The surrounding and filled
colors of each task communicate whether it is on time, due, or overdue
and the priority level relative to other tasks, respectively. When there
are overdue tasks in the calendar (surrounded by red), the user can
adjust the number of work hours/day under “edit view” to see how many
hours/day are required to complete tasks on time.

The calendar is automatically saved to the device when the session
closes. The calendar can also be exported to Google Calendar through a
downloadable csv file (when importing the csv in Google Calendar, the
blocks of tasks from the Shiny App will be added to the corresponding
day, starting at 10 am.)

### Link to application

https://joeomatoi.shinyapps.io/shiny_task_planner/
