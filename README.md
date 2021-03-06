# Hack-the-North-2018-Frontend-Challenge

Hack the North 2018 Frontend Challenge made using HTML/CSS and JavaScript(jQuery).


## How To Use this WebApp

Simply clone the repo then open the HTML file with the browser of your choice. CLick on the buttons on the nav bar to jump to a certain section. In the schedule section, hover on an item to see it's description (if there's any given) and click on an item to add it to your personal schedule. You can also search for events based on their title or tags using the search bar. In the personal schedule section, hover to check an item's description and click to delete an item from your personal schedule. 


## UX/UI Design

My goal for this web app was to create a simple yet aesthetic design which I aimed to achieve by utilizing the classic Hack the North colour scheme (white and blue shades) and various hover effects. I also colour coded each event by it's start time during the day. Events that are closer to midnight are dark blue and events that are closer to noon are a lighter shade of blue but their distinct shade is dependent on their distance from these two endpoints. This was accomplished by using a trig function to model the hex value of the colour for each event.


## Next Steps

Overall, I'm pleased with the progress I have made with this project in such a short amount of time. I completed this project in between studying for midterms and preparing for interviews so I definitely didn't have as much time as I would've liked to complete this project. On the other hand, completing this project amidst a ferocious sea of midterms and interviews push me to dissect problems and complete subgoals much more quickly and effectively.

If given more time, I would use cookies to store the user's saved events so that they are not wiped during a refresh. This would be done simply by storing a JSON array with the saved events.

Some next steps for this project include: 
* Converting the schedule from a list view into a table format with 3 columns (for times-similar to a classic online schedule, titles and locations) to further organize the information and improve readability. 
* Add icons for event tags (ie. food, logistics, etc).
* Add more animations (interesting ones similar to the gears on the Hack the North 2017 website, and a circular progress bar for the countdown timer).
* Transfer the personal schedule to a new page.
* Improve the background by using various Hack the North wallpapers that align with the colour scheme.
* Cleaning up the code and improving efficiency.


## Some Useful Features that Could Be Implemented in the Future

* Leading off of the example given about specific directions for each hacker throughout the hackathon (creating a build-your-own-adventure theme) we can aggregate all the travel data to find which routes on campus are the busiest at certain times so at peak times we can locate exactly which areas of campus to focus volunteer/organizer efforts to guide hackers to their destination.
* Also stemming from the example, we can include times and alerts to leave for an event given the hacker's location and expected travel time (which can be queried from Google Maps API). 
* We can also suggest similar events for empty time slots on a hacker's personal schedule (similar to YouTube suggesting similar videos).
* Can also create a list of events and after implementing a friend feature like Facebook (where you can add your teammates/other friends at Hack the North) you can see which other friends are going to the same event. We can also potentially use these for a teammate tracker so you'll know exactly where your teammates are so you won't get lost.


## Using Performance Metrics

Some possible performance metrics that could be implemented could keep track of the number of people that add an event to their personal schedule and the number of searches for titles/tags to see which are most popular and focus on these initiatives in the future. Also, depending on how early the majority of users add events to their personal schedule - the organizing team can anticipate major fluctuations (if they are early enough) in popularity of events so that resources (food, chairs, etc) are allocated accordingly. 

