# RunKeeper Import

Submitted by: [@jordanmerrick](https://twitter.com/jordanmerrick)

Imports the running workout data from an exported RunKeeper data CSV file into Health, logging with each the date and time, duration, distance and calories burned.

Export your data from RunKeeper and place the CSV file somewhere in Dropbox (or modify the workflow if you want to access this file in another way). Exporting your data can be done in your RunKeeper Settings, where you’ll need to specify a date range. If you’re still going to be using RunKeeper and continuing to workouts to Health, I suggest looking through your Health workout history to see exactly when RunKeeper started logging runs to Health and using this as the end date, otherwise you’ll end up with duplicate workouts, logged by RunKeeper and Workflow.

The exported data will contain a number of files, but this workflow just uses the **cardioActivities.csv** file. Confirm that the column headers in the file are as follows:

  * **Date**
  * **Type**
  * Route Name
  * **Distance**
  * **Duration**
  * Average Pace
  * Average Speed
  * **Calories Burned**
  * Climb
  * Average Heart Rate
  * Notes
  * GPX File

The list items in bold represents the data that this workflow will use.

Edit the workflow and updated the “Log Workout” action to specify the unit of distance you need to use. By default, it’s in Kilometers, so if all your workout data is in Miles, change this before continuing.

Run the workflow, choose “Test” mode and select the CSV file in Dropbox that was exported from RunKeeper. The workflow will begin and may take about 10–30 seconds to run, depending on how much historic data you have.

Provided Workflow doesn’t display any errors, you should see Workflow output all of your runs as a list in a basic text format with all of our workout data (note that this workflow converts any workout durations into seconds). If you’re happy that this all looks correct, re-run the workflow in “Live” mode.