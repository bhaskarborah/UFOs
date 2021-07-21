#   UFOs-Analysis

## Overview of Project

Dana is a Data Journalist. She has the freedom to write about the topic that she chooses to. She wants to write about McMinnville, Oregon, as it is, firstly, an opportunity to revisit the memories and people in het hometown, but secondly, and more importantly, she would get to write about UFOs as McMinniville is noted for its sightings of UFOs and also has an annual gathering.
Dana already has a Javascript (js) file which has data related to the UFO sightings like city, state, country, state, shape and types of sightings.
The objective of this project is to, read the JavaScript file and load the data as a dynamic table. Also provide the ability to filter the data in the table and display the results in a tidy HTML page page with the article heading and details, table details and easy filters to view the required data. 

## Purpose

The required input data is available in a JavaScript file.

The purpose of this project is to provide the below deliverables:

Deliverable 1: Filter UFO sightings on multiple criteria
Deliverable 2: A written report on the UFO analysis

## Results

Deliverable 1: Filter UFO sightings on multiple criteria

The UFO sightings can be filtered using the below code:

The filterTable() function is used to filter the UFO sightings based on the "input" data. This "input" data has to be used in the index.html file which invokes the app.js file.

![Screen Shot 2021-07-20 at 4.37.28 PM](https://i.imgur.com/GScVwU0.png)

The code in the index.html file used for the filter is as below:

![Screen Shot 2021-07-20 at 4.40.02 PM](https://i.imgur.com/AFQf1HK.png)

The data is visualized as below in the html page:
![Screen Shot 2021-07-20 at 4.43.04 PM](https://i.imgur.com/i9hxAIF.png)

The data with a filter criteria applied:

![Screen Shot 2021-07-20 at 4.44.17 PM](https://i.imgur.com/Y5bcNfC.png)




# UFOs-Summary

The required details have been displayed into a html page using JavaScript and Bootstrap/HTML.

The "UFO Sightings" Navigation Bar/Switch can be used to refresh the contents of the site.
![Screen Shot 2021-07-20 at 4.47.35 PM](https://i.imgur.com/0me9XCO.png)

And also various filters based on date, city, state, country and shape can be implemented.

For example, below is a filter based on date, city, state and country:
![Screen Shot 2021-07-20 at 4.52.03 PM](https://i.imgur.com/T5amay1.png)

One drawback of this design is that, the user has to enter the fields manually to set up the filter. This requires the user to have to take a look at the data in the table and understand the values in the fields which might be time consuming based on the data in the table.

One way to address this drawback is to have drop down lists instead of letting the user fill up the data. The values selected in the initial filer say "date" (from the drop down list) will only present the values belonging to that date in the next filter "city" (from a drop down list) and so on. This will eliminate the requirement of having all the values in the drop down list.
Standardization of the data in the table would also be required as we begin to deal with larger data set. It would help to have the data in various fields to follow a uniform standard, say for example all the state names should be in capital letters, the date format should be "yyyy-mm-dd" etc.



