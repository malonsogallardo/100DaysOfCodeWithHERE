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

### Days 1-5 of #100DaysOfCode
<details>
<summary> Expand </summary>

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
</details>

### Days 6-10 of #100DaysOfCode
<details>
<summary> Expand </summary>

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
</details>

### Days 11-15 of #100DaysOfCode
<details>
<summary> Expand </summary>

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
</details>

### Days 16-20 of #100DaysOfCode
<details>
<summary> Expand </summary>

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
</details>

### Days 21-25 of #100DaysOfCode
<details>
<summary> Expand </summary>

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
</details>

### Days 26-30 of #100DaysOfCode
<details>
<summary> Expand </summary>

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
</details>

### Days 31-35 of #100DaysOfCode
<details>
<summary> Expand </summary>

### [Day 31 Browse with name](/Day%2031)
- Use the 'Browse' endpoint of the Geocoding and Search API to look for a 'Museum'
- Do a simple search with just the 'name'
### [Day 32 Browse + categories](/Day%2032)
- Add to the search query from Day 31 to add a level 3 category search.
-  Look for 'History Museums' around you while writing 'Museum' in the name field
### [Day 33 Browse + Food Categories+ Takeout 🌮](/Day%2033)
- Modify the search request from day 32 to use the level 2 food categories for Mexican food
- Make sure that you only search for restaurants which serve ' takeout' .
### [Day 34 Lookup](/Day%2034)
- Note the 'id' from one of the places in the results from day 33
- Use this id to 'lookup' the specific place
### [Day 35 Reverse geocoder](/Day%2035)
- You know where a friend lives but can't find their postal address to send them a gift ?
- Use the reverse geocoder to get the postal address from the position on the map {lat: ,lng: }
</details>

### Days 36-40 of #100DaysOfCode
<details>
<summary> Expand </summary>

### [Day 36 Geofencing Creating a WKT file](/Day%2036)
- Draw a polygon around a place that is interesting to you and save it in a WKT file.
### [Day 37 Geofencing Uploading a WKT file](/Day%2037)
- Upload the polygon you created in day 36 as a layer so you can use as a geofence later
### [Day 38 Geofencing retrieve layer](/Day%2038)
- Retrieve the ID of the polygon that you uploaded as a layer on day 37
### [Day 39 Geofencing To be or not to be](/Day%2039)
- Given a point with latitude and longitude and your layer from day 37, use one of our APIs to check whether the point is inside your layer or not.
- Hint: Check out the link: https://t.her.is/35zshEV
### [Day 40 Geofence Almost there](/Day%2040)
- Update your function from day 39 so that it’ll determine whether the point is within 100 meter proximity of your layer or not.
</details>

### Days 41-45 of #100DaysOfCode
<details>
<summary> Expand </summary>

### [Day 41 Routing A to B](/Day%2041)
- Determine two random locations on the map that are navigable by car.
- Get the shortest route for car to drive between those locations in the form of a polyline.
### [Day 42 Routing : Draw the route](/Day%2042)
- Use the flexible polyline received as the result from Day 41
- Draw the first route on the map and color it #034F84
### [Day 43 Routing : Alternatives](/Day%2043)
- Request for 3 alternative routes for the route received on Day 42
### [Day 44 Routing : Timing is important](/Day%2044)
- Set the departure time to 9 AM for the route 
- Set the departure time to 3 PM for the same route 
- Compare the difference between all received routes
### [Day 45 Routing : Summary](/Day%2045)
- Get the summary of the time required and distance covered for any of the routes you calculated in the previous days.
</details>

### Days 46-50 of #100DaysOfCode
<details>
<summary> Expand </summary>

### [Day 46 Routing : Waypoints](/Day%2046)
- Add a waypoint which falls between the route from day 41 
- Draw a route including this waypoint
### [Day 47 Routing : Driving Instructions](/Day%2047)
- Print out driving instructions and actions for the first route received on Day 46
### [Day 48 Routing : Speed Limit](/Day%2048)
- Find out the speed limit on the route for Day 46
### [Day 49 Routing : Stop Duration](/Day%2049)
- Add a stopover of 900 seconds to the waypoint from day 46
- Log the waiting time with instructions
### [Day 50 Routing : Pedestrian](/Day%2050)
- Get a walking route between two points
- Draw the route with a dashed line 

</details>

### Days 51-55 of #100DaysOfCode
<details>
<summary> Expand </summary>

### [Day 51 Routing :  Avoid routing feature](/Day%2051)
- For the pedestrian route from day 50,  avoid parks
- Use Routing v7 to do this
### [Day 52 Routing : Bicycle](/Day%2052)
- Get a bicycle route between two points
- Use Routing v7 to do this
### [Day 53 Routing : Avoid routing feature](/Day%2053)
- For the bicycle route from day 52,  avoid dirt roads
- Use Routing v7 to do this  
### [Day 54 Routing : Public Transport](/Day%2054)
- Get a public transport route between two points
- Use Routing v7 to do this
### [Day 55 Routing : Avoid Buses](/Day%2055)
- For the public transport route for day 54, get a route without buses
- Use Routing v7 to do this
</details>

### Days 56-60 of #100DaysOfCode
<details>
<summary> Coming soon ... </summary>


</details>

### Days 61-65 of #100DaysOfCode
<details>
<summary> Coming soon ... </summary>


</details>

### Days 66-70 of #100DaysOfCode
<details>
<summary> Coming soon ... </summary>


</details>

### Days 71-75 of #100DaysOfCode
<details>
<summary> Coming soon ... </summary>


</details>

### Days 76-80 of #100DaysOfCode
<details>
<summary> Coming soon ... </summary>


</details>

### Days 81-85 of #100DaysOfCode
<details>
<summary> Coming soon ... </summary>


</details>

### Days 86-90 of #100DaysOfCode
<details>
<summary> Coming soon ... </summary>


</details>

### Days 91-95 of #100DaysOfCode
<details>
<summary> Coming soon ... </summary>


</details>

### Days 96-100 of #100DaysOfCode
<details>
<summary> Coming soon ... </summary>


</details>



 
