# HW5_Planner
A simple planner application. 


Acceptance Criteria:
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persists.

Everytime that the save button is clicked on the page, the setItem() function saves the text from the textarea element and assigns it a key value - which is correlated to the ID of the container that it was written in. My application then posts this to the local storage of the web browser, where it can be revistied. 

my current application version satisfies all but the final part of the acceptance criteria: keeping the localally stored item posted on refresh. 

