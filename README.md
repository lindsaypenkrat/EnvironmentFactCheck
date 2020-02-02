# About the code

## What is it?
A chrome browser extension that helps you become better informed about the environment. It highlights websites that provide fake information and gives you points when you use environmentally accurate sources.

## Why did we make it?

We want to create a more environmentally concious society in today's era of misinformation. This starts by making it easier for everyone to choose reliable sources!

## Who are we and where did we make it?

We made it for TechTogetherBoston2020, a hackathon for women and non-binary hackers. Our team had 4 members:

      - Deanna Castano
      - Tanishka Porwal
      - Lindsay Penkrat
      - Emily Amspoker
      

# File breakdowns

## Background.js

Background.js created the background page for the extension. For our purposes, we used it to define key-value pairs in storage that we would later use in our other js programs.

## Popup.html

Popup.html created the visual window of the extension. It was formatted using an open source design system, PatternFly. The font came from Adobe Fonts and was linked in using a stylesheet generated by Adobe Fonts.

## Popup.js

This is the .js file that interacts with the HTML. It fetches values using a key for everything that needed to be displayed (level of reliability, description of what that level means, number of user points, etc.), and would then display those values by using documend.getElementById.

## Content.js

This script interacts with the webpage the user is on. It parses the url of the page, and then compares it to a list of reputable environmental sites and a list of sites known for deliberately publishing misinformation.

## Navigate.js

This script navigates away from the page the user is currently on, and to our [website](eamspoker.github.io/Fakenewsdetector), which is hosted on Github pages, and is also available on [a public repository](https://github.com/eamspoker/Fakenewsdetector).

## images/

This folder contains all of our image resources, including favicons and logos.

## css/

This folder contains the style resources and assets from Patternfly.


