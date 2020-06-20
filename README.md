# Daily Calendar
A simple calendar application that allows a user to save events for each hour of the day. This app runs in the browser and features dynamically updated HTML and CSS powered by jQuery.

## Functionality Highlights
* Pulls current week day, full date, and current time via Moment.js
* Outputs week day and full date in the header
* Time blocks pull actual hours
* If time block is in the past, circle and date are gray and textarea is muted
* If time block is in the future, circle is blue and date and textarea are at full opacity
* If time block is current, circle animates with border pulse
* Time blocks are automatically populated via a for loop
* Data is stored to local storage on form submit
* If data is stored in local storage, it auto populates on page load
* If time is after work hours, header color and image change to night mode and alert is diplayed
* 6 PM block is populated after loop so it can be muted as soon as current time hits 6 PM
* Textarea height gets taller if text is longer than the default height

## Todos
* ~~Pull week day, long date, and current time via Moment.js~~
* ~~Display week day, and long date in the header~~
* ~~Store data to local storage when submitted~~
* ~~Pull data from local storage to automatically appear on page refresh~~
* ~~Assign time blocks to actual times~~
* ~~If time block is in the past, gray the circle and time, and mute the textarea~~
* ~~If time block is current hour, display blue circle with animation~~
* ~~If time block is in the future, display blue circle~~
* ~~If time isn't between 9-5, display after hours message~~
* ~~If time isn't between 9-5, swap out header day image with night image~~
* ~~If time isn't between 9-5, update header color~~
* ~~Utilize loops to populate the data on the page~~
* ~~Update last time block form to have a border-bottom~~
* ~~Have the textarea height get taller if the text is longer than the default height~~
* Automatically "save" an entry by hitting the enter key or clicking out of the textarea
* Update textarea background color if there's content in it
