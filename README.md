Work Day Scheduler

The Task

Create a simple calendar application that allows a user to save events for each hour of the day by modifying starter code. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

Use the [Moment.js](https://momentjs.com/) library to work with date and time. Be sure to read the documentation carefully and concentrate on using Moment.js in the browser.

## User Story

```
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

## Acceptance Criteria

```
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with time blocks for standard business hours
WHEN I view the time blocks for that day
THEN each time block is color-coded to indicate whether it is in the past, present, or future
WHEN I click into a time block
THEN I can enter an event
WHEN I click the save button for that time block
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
```

Finished Demo
![demoGif](https://github.com/timvvoodman/Work-Day-Scheduler/blob/master/Work_Day_Scheduler_Demo.gif)

Reflections:

- I actually found it was easier to add some of my own CSS rather that match all the included css. Something I'll have to pay close attention to durring the homework review.
- I was unable to find way to avoid repeating code in lines 85 - 153. I beleive this is beacuase of the way I desiced to dynamicaly add unique IDs to the html in the jQuery template in lines 76-81.
