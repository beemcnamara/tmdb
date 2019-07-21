# TMDB TASK
TMDB Task is a single page application using JavaScript to integrate with an API and use the data to display a list of movies.

## Installation
Download the files into one directory and click on the index.html file to open the page in your browser.

## Notes
I initially wrote indexv1.html which has a fixed top filter bar. When tested on a much smaller screen such as a mobile phone the filter bar is all that is displayed. I rewrote this to index.html which has a side bar. This is an improvement however on smaller screens the images and the sidebar cannot both sit fully within the screen so this will need development if it is required to be viewable on smaller mobile screens. To resolve this I would consider making the side bar a slide out bar or having a drop down menu from the very top showing all the filters.

I have tested this app on Chrome, Edge, Firefox and Opera and it works well in all. The only problem I have come across is that it loads as expected in Firefox but if you refresh the page (F5) after it's initial load it won't load again. I wondered whether this might be a connection/speed/timing issue and so added some setTimeouts for various scripts but this made no difference. This issue will need further research to resolve.