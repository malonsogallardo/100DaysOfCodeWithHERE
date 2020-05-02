![100DaysOfCode](img/100daysofcode.jpg) 



<p> An amazing way to learn a new skill is to learn a little bit of it , every day. We at HERE Technologies want you to get acquainted with <strong>Location Technology</strong> through <strong>Map APIs </strong> provided by us by launching <strong>Days Of Code with HERE</strong></p>
<!--more-->
<p>
    Starting from the 1<sup>st</sup> of April 2020, we have been posting 1 task <strong>every day</strong> on our twitter handle <a href="https://twitter.com/heredev/">@heredev</a> and will be doing this for <strong>100 days</strong>. In solving the tasks, you will be using the HERE JavaScript APIs found at <a href="www.developer.here.com/documentation">developer.here.com</a>. The <strong>Documentation</strong> section will help you find the solutions. 
    Feel free to tweet your solutions back at us with the tags <strong>#100DaysOfCode</strong> and <strong>#100DaysOfCodeWithHERE</strong>.<br>
    We will also provide you the solutions in various forms:
</p>
<ul>
    <li> Preview video on twitter with solution to the <strong>previous day task</strong></li>
    <li> Blogpost with solutions for <strong> 5 days of tasks</strong> on our <a href="https://developer.here.com/blog/topic/100daysofcode">developer blogs</a> </li>
    <li> Video tutorial with solutions for <strong> 5 days of tasks</strong> on <a href="https://www.youtube.com/user/heremaps/playlists"> YouTube</a></li>
</ul>
<p>If you have any questions during the 100 Days, feel free to dm us , post your questions on our <a href="www.developer.here.com/blog">developer blogs</a> and <a href="https://www.youtube.com/watch?v=dvSHOLI4QQc&list=PLTlZUhyLwZTcV_b8Z8Va8JYsH2CQnOwFS"> YouTube</a> videos or post the question on our <a href="https://t.her.is/slack">slack channel</a><br>
You will also find the day wise code in this repo.<br>
Happy coding with <strong>100DaysOfCode</strong>!</p>

# Tasks completed so far
### Day 0/100 : Get your credentials by signing up for a freemium account at [developer.here.com](https://developer.here.com/)

### [Day 1/100:  Page Frame](/Day%201)
- Create the frame for an HTML + JS web page
- Add HERE map core and map services source within the <head></head> tags 
### [Day 2/100 : Create div for holding map](/Day%202)
- Create div for holding map - width = 100% of screen , height = 80% of screen, background colour of your choice.
- initialize platform with the JavaScript apiKey
### [Day 3/100 : Load Map](/Day%203) 
- define the center of the map with latitude and longitude
- initialize VECTOR map with default layer, center of map and zoom level 
### [Day 4/100 : Map UI - Control Panel](/Day%204)
- Add zoom in and out buttons to the map.
- Also add ui element to change map type (satellite, traffic) after loading.
### [Day 5/100 : Map UI- map event](/Day%205)
- Add panning capability to the map
### [Day 6/100 : Map Tilt](/Day%206) 
- Set the map to tilt at a 60º angle
- Align the map such that the top of the map is the West half of the globe
### [Day 7/100 : Position](/Day%207)
- Get position from your browser  * Hint check out our blogs
### [Day 8/100 : Marker](/Day%208) 
- Add basic marker at current position
### [Day 9/100 :  Marker SVG](/Day%209)
- Change the marker from the default marker to an svg marker
- The maker can be a white circle inside a green circle like the one on our web app Here We Go 
### [Day 10/100 : Click for position](/Day%2010)
- add event to log the position when you click anywhere on the map
### [Day 11/100 : Marker data](/Day%2011)
- Place an image as a marker where you clicked on the map. 
- Add the text " I'm Here " to the marker as marker data 
### [Day 12/1000 :  Info-bubble](/Day%2012) 
- Display an info-bubble on tapping the marker
- show the marker data as the info in the bubble.
### [Day 13 dragging the marker](/Day%2013)
- add capabilities to drag a marker and position it in another place on the screen
- Hint: You will have to write event listeners for when you start the drag, during the drag and end of drag
### [Day 14 Drawing a circle](/Day%2014)
- Draw a circle of radius 10 km
- Let the center be the new position after the marker was dragged
### [Day 15 Customizing the circle](/Day%2015)
- Fill in the circle with a color of your choice
- Give it a darker border of width 4px
### [Day 16 Playing with fonts](/Day%2016)
- Change the map font on Load
- Hint ;) Take a look at map styles
### [Day 17 Styling after load](/Day%2017)
- Create a button called highlight hospitals
- Change the colour of all hospitals in the world to a bright red on clicking the button
- Hint- use map style on load
### [Day 18 Languages](/Day%2018)
- Change the default display language of the map to anything other than English 
### [Day 19 Control panel](/Day%2019)
- Change the position of the map control panel to the top right of the map
### [Day 20 Geocoder free form search](/Day%2020)
- Change the unit of the map to see distance in miles
### [Day 21 What's meters, I understand only miles](/Day%2021)
- Use the geocoder and Search service to conduct a free form search for 'hauptstraße' 
- Choose any street with a common name instead, and let us know how many results you get!
### [Day 22 Limit results](/Day%2022)
- Limit the results from the task on Day 21 to 5 results
### [Day 23 Geocoder limit by country](/Day%2023)
- Limit the results from the task on Day 22 to the country ' Germany' 
- If you are using a street near you, limit the search to your country 
### [Day 24 Geocoder with a qualified query](/Day%2024)
- Instead of the free form search, use a structured search where street = hauptstraße , city = Berlin, Country = Germany
- Customize this according to the street you want in the result.
### [Day 25 Geocoder access to the building](/Day%2025)
- Search for 'Invalidenstraße 116, Berlin'
- Place a marker on the access point of the building.
### [Day 26 Geocoder discover](/Day%2026)
- Use the discover endpoint of the Geocoder and search for ‘markets’
- specify a point where you want to discover the markets 
### [Day 27 Discover places in a radius](/Day%2027)
- Using the discover endpoint, search for markets in a 1km radius
### [Day 28 Discover distance](/Day%2028)
- Note down the 'distance' parameter of each of the results from the result of Day 27
- Display the result in an info-bubble for every result.
### [Day 29 Autosuggest](/Day%2029)
- I am so tired that I need Starbucks and cannot even type it completely
- Use the autosuggest endpoint to search for an incomplete query 'star' near you. 
### [Day 30 Autosuggest bounding box](/Day%2030)
- Repeat the query from day 29
- This time, restrict your search within a box of 4 blocks
- Hint : check the parameter bounding box

 
