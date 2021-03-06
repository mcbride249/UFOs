# **UFOs**

## **Project Overview**

The purpose of this analysis was to JavaScript to build a dynamic web page that could accept user inouts and visually adjust accordingly to reflect that interaction. This was done by inserting our JavaScript code into an HTML page. CSS, Bootstrap and Chrome DevTools were used to cutomize the page and test the code throughout. The project was centrered on inserting a table populated with data that we wanted to display into the web page, and then adding filters to the table which would allow users to refine their search. A header, displayed along with an imported image, a summary, and an article were also included on the web page. The end result was to have a web page that presented the data, that was visually appealing, and that was interactive.  

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Goals**

1. Build a table function, loop through each function and append a row to the HTML table, adding eavch object into a cell.

2. Add filters.

3. Design the web page with Bootstrap.

4. Customize the page.




---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Summary**

1. Build a table function, loop through each function and append a row to the HTML table, adding each object into a cell.

The code that created the table, looped through the data, and adding neww data to the table in aeach cell can be seen here:   

![Goal 1](https://user-images.githubusercontent.com/92111396/149159404-704f3867-46e4-4f9c-a6b3-783eca77a66f.PNG)
https://github.com/mcbride249/UFOs/blob/main/Screenshots/Goal%201.PNG

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2. Add filters.

The filter function that can be seen in the following block of code used the D3.js library. This allowed us to "listen for events", in this case the user clicking the button on the filter, once their search criteria had been imported.  

![Goal 2](https://user-images.githubusercontent.com/92111396/149160157-38251ab3-0501-4a6a-85cf-bc450ffca34f.PNG)
https://github.com/mcbride249/UFOs/blob/main/Screenshots/Goal%202.PNG

The if statement allowed the code to check for a date and if one was present, only the dta for that row would be returned. 

Finally, after the data had been filtered, the table needed to be rebuilt using the filtered data. This is was done by passing the filtered data through the build table function. 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3. Design the web page with Bootstrap.

The below image shows the design ffor the web page that Dana wants to create.

![Bootstrap Grid System](https://user-images.githubusercontent.com/92111396/149162066-77cdc051-3fc7-49ef-998a-ead85c52f839.png)
https://github.com/mcbride249/UFOs/blob/main/Screenshots/Bootstrap%20Grid%20System.png

We designed the web page using HTML using the Bootstrap Grid System. A link to the HTML code that was used to design the system can be found here: https://github.com/mcbride249/UFOs/blob/main/index.html.

While the design itself is relatively self explanatory, scripts were added to the bottom of the code to link our HTML code to the D#.js library, as well as linking the file that contains our data, and the JavaScript that will run our code. 

![Goal 3](https://user-images.githubusercontent.com/92111396/149163577-d650265b-5c2e-47fa-9933-75c98c8585e6.PNG)
https://github.com/mcbride249/UFOs/blob/main/Screenshots/Goal%203.PNG

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4. Customize the page.

The page was customized by changing the font and background via the CSS file. The most striking design amendment was the importation of a background image to the jumbotron.

The final design image for the page can be seen below both with filtered and unfiltered data.

Unfiltered:
![Goal 4-1 - Unfiltered](https://user-images.githubusercontent.com/92111396/149165506-4b75501a-2eb0-40d5-af58-1963f924f641.PNG)
https://github.com/mcbride249/UFOs/blob/main/Screenshots/Goal%204-1%20-%20Unfiltered.PNG

Filtered:
![Goal 4 - Filtered](https://user-images.githubusercontent.com/92111396/149165483-a5327a4a-1107-4ded-a437-b03164d7d621.PNG)
https://github.com/mcbride249/UFOs/blob/main/Screenshots/Goal%204%20-%20Filtered.PNG


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Resources**

-Data Source: ufo_starterCode.js, data.js

-Images: nasa.jpg

-Software: Python 3.7.10, Visual Studio Code, 1.38.1, 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Module 11 - Challenge** 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Purpose**

The purpose of this task was to improve upon the dynamic webpage that we already created for Dana by allowing users to filter along multiple criteria beyond the date, such as city, state, country, and shape, in which the UFOs sighting occurred. This was done by creating four more list elements based on the search criteria in the HTML index file. Within the app.js file, a variable "var filters = {}" was created to track all of the filters, while a new function was also created to update the filters and save each element of the filter that was changed(steps 3-5). Ultimately, the dynamic web page was updated to include 5 filters, that automatically reacted user input based on their specific search criteria, and negating the need for a search button.     

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Results**

The below image shows the unfiltered, completed page, as it is displayed upon opening.

![Results - Image 1 -  Unfiltered](https://user-images.githubusercontent.com/92111396/149171478-29bf2eeb-441b-4499-90d3-94bfde7edcde.PNG)
https://github.com/mcbride249/UFOs/blob/main/Screenshots/Results%20-%20Image%201%20-%20%20Unfiltered.PNG



The below image shows the filtered page, based on all seach criteria, exluding "city" to demonstrate that the filters work.

![Results - Image 2 - Filtered](https://user-images.githubusercontent.com/92111396/149171501-4d616758-943b-45e0-be75-c11eb323d20a.PNG)
https://github.com/mcbride249/UFOs/blob/main/Screenshots/Results%20-%20Image%202%20-%20Filtered.PNG



The below image shows the filtered page using all filters.

![Results - Image 3 - Filtered](https://user-images.githubusercontent.com/92111396/149171512-5eb801df-fdfd-4611-998a-943169fb5ae9.PNG)
https://github.com/mcbride249/UFOs/blob/main/Screenshots/Results%20-%20Image%203%20-%20Filtered.PNG



**How To Perform A Search**

Searches can be performed by entering the search criteria from the table into corresponding filter.

Searches can be refined based on the date, city, state, country, in which the event occurred or based on the shape of the UFO.

![Results - Table Filter Headers](https://user-images.githubusercontent.com/92111396/149174115-8ce99008-49ed-453e-85fa-a85b8b793e8c.PNG)

https://github.com/mcbride249/UFOs/blob/main/Screenshots/Results%20-%20Table%20Filter%20Headers.PNG

To search for a specific field simply type the search parameters into the filtered areas. The filters themselves contain an example of how data must be inputted.

![Results - Filter Search Criteria](https://user-images.githubusercontent.com/92111396/149174139-5dcd4bc0-125c-456b-b218-a3cc4bd47b7e.PNG)

https://github.com/mcbride249/UFOs/blob/main/Screenshots/Results%20-%20Filter%20Search%20Criteria.PNG


To clear the filter, simply delete the data that was entered in each filter.


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Summary**

While the dynamic webpage performs its function and is visually appealing, there are a number of drawbacks to the page itself and ways that it can be improved that should  be suggested to Dana.

The most obvious drawback is the need to erase your input in the filters in order to return to the full set of data in the table. The solution to this would be to create a clear button, that erased all inputted data from the filters, thereby returning the full table data and eliminating the need for the user to manually erase the text in each filter. This could be accomplished by creating a button similar to that we originally created for Dana: <button type = ???reset??? value = ???Reset???>Reset</button> or something similar.

Additional improvements that I would recommend include removing the country as a search criterion, as only one data row contains information from outside of the United States, and as such entering the country information does not greatly reduce the amount of information that is present. Perhaps when additional data gets added from outside the United States this filter could be readded. If we are going to include data from outside the United States, the ???State??? column should be updated to read ???State/Province??? as many countries (including the one other country currently listed on the table) utilize a provincial system. 

I would also not restrict the manner in which data could be entered into the filter. Specifically, I would allow for capitalization of place names, or allow for full state names to be entered, as many users may simply input this data assuming it will work, however no data will be returned. Similarly, I would recommend double digit months and days (beginning with 0s) be eligible to be entered into the filters in addition to what is currently in place (i.e.. 01/13/2013, and 03/09/2015) as users may do this instinctually. Making these small updates will increase the user experience.








