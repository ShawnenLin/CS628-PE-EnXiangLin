Input
The application presents a list of available cities. The list is augmented by having users enter city, country, and population in given text entry fields and click on "Add City."

Process
Upon clicking on "Add City", the application captures city details entered and incorporates the new city to the current list. The application makes use of React's useState to store both the list of cities and user-provided input. As soon as a city is added, the application redirects the user to the list of cities. The application also makes every city's name in the list appear in link format, and on click, redirects to a detail page presenting extra details on the city.

Output 
The end result is a current, click-able list of cities. If clicked, the application offers extensive details on the city, such as country and population, in an efficient and accessible format to view and incorporate city data.