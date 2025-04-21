This project is a Digital Clock built using HTML, CSS, and JavaScript. It displays the current time in hours, minutes, and seconds, updating every second in real-time. The design features a modern design with a gradient background and glassmorphism effects using CSS backdrop-filter. The time units are displayed in a styled container with labels ("HOURS", "MINS", "SEC") shown dynamically using pseudo-elements.

Tools and Languages Used:
HTML: for the structure of the clock
CSS: for styling and animations.
JavaScript: to fetch and update the real-time clock every second


steps to build and run it:
HTML Structure:
Created a div with the class hero as the main wrapper. Inside it, added a container that holds the clock. Used span elements to display hours, minutes, and seconds with IDs (hrs, min, sec) for JavaScript to target.

CSS Styling:
Applied a gradient background to the .hero section using linear-gradient(). Styled the .container to center it using position: absolute and transform: translate(-50%, -50%). Added a glass effect to .clock using backdrop-filter: blur(40px). Used ::before and ::after to add colorful decorative shapes behind the clock. Set font sizes and positions for the time display using .clock span and styled labels like "HOURS", "MINS", and "SEC" using ::after.

JavaScript Functionality:
Selected the span elements using getElementById. Used setInterval() to update the clock every second. Created a Date object and extracted the current hours, minutes, and seconds. Formatted the time to always show two digits (06 instead of 6). Injected the formatted time values into the HTML using innerHTML.

Challenges that I faced during creating this digital clock:
I chose to create digital clock from the playlist because i am a beginner. So I thought this would be easy for me to learn and build the code. The main problem that I faced was the language javascript and css. I learnt a lot while creating the digital clock such as how to design it, how to change colours and background and fonts, how to set the time with javascript inside innerhtml. I firstly added the colour red as background, when i tried to change it by using .clock, it was not changing the colour. Lastly i figured out that i had to remove the colour red from .container .
