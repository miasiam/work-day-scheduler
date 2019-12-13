Create a simple calendar application that allows the user to save events for each hour of the day. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

The app should display standard business hours (9 a.m. to 5 p.m.). Each time slot should represent one hour and contain the following:

* The time

* A field to hold user input

* A save button

Clicking on the save button will store the time and user input in `localStorage`.

Near the top of the calendar, the application should display the current day. Additionally, each hour should be color coded to reflect whether the time slot is in the past, the present, or the future. This will change depending on the time of day.

You'll need to use the [Moment.js](https://momentjs.com/) library to work with date and time. Be sure to read the documentation carefully and concentrate on using Moment.js in the browser.

![day planner demo](./Assets/05-Third-Party-APIs-homework-demo.gif)

## User Story

AS AN employee with a busy schedule

I WANT to add important events to a daily planner

SO THAT I can manage my time effectively 

## Business Context

Poor time management can result in missed meetings and deadlines or create the appearance of unprofessionalism. A daily planner allows employees to see their day at a glance, schedule time effectively, and improve productivity. 

## Minimum Requirements

* Functional, deployed application.

* GitHub repository with a unique name and a README describing project.
<!-- compleyed -->

* The application displays timeblocks for standard business hours (9 a.m. to 5 p.m.).
<!-- completed -->

* Each timeblock contains an input field and save button.
<!-- completed -->

* Clicking a timeblock's "Save" button stores the input text in local storage, allowing the text to persist when the application is refreshed.
<!-- completed, pressing enter does not work and will signal a pulse -->

* The current day is displayed at the top of the calendar.
<!-- completed -->

* Each timeblock is color coded to indicate whether it is in a past, present, or future hour.
<!-- this still needs to be applied -->

Near the top of the calendar, the application should display the current day.
>>>>>>> 8132fa60ffa7dbbf10e33db64ca8893461e2e694
