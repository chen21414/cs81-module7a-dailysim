# Reflection – Daily Schedule Simulator

## What was your approach to designing the schedule?
My approach was to create a schedule based on a typical weekday in my life. I included activities such as waking up, going to work, checking emails, processing invoices, studying JavaScript, relaxing, and going to sleep. 

## What was one challenge or unexpected behavior you encountered?
One challenge was understanding that setTimeout() does not pause the entire JavaScript program. JavaScript continues reading the remaining code and schedules each callback to run later.

At first, I thought the program would wait for one activity to finish before scheduling the next activity. As a result, all the timers are created almost right away. 

## What does this assignment teach you about async code?
This assignment taught me that asynchronous code allows JavaScript to schedule tasks without stopping the rest of the program. A regular synchronous runs from top to bottom, with each statement completing before the next statement begins.

## What creative element did you add?
I added a random mood check as the creative element. The program stores several moods in an array and uses Math.random() to select one of them.

## How does this project simulate or differ from real-world schedules?
The project simulates a real-world schedule by displaying activities in top down order. Each timer represents the amount of time between daily activities. It helps demonstrate how events can be scheduled to happen at different times.
