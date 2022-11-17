# UFOs are Real(?)

## Overview of this project
In this project, I developed a website that holds a table of data about UFO's and added dynamic functionality to the website such that the user can filter the data according to their liking. I have added several filter textbox for which the user can filter the data by. 

Here is a sample view of what the website looks like:
![Website View](/static/images/sample.png)

## Results
Using this website is very simple. First, we have a navigation bar at the top with a link and the link just links back to this same page. Next, we have the header of this article. Underneath the header, we have the article and underneath the article are the data table. This data table is filterable. And there are filter search text boxes beside it. You can simultaneously filter everything such as: Date, City, State, Country and Shape as shown in the following image: 
> ![filter all](/static/images/filterAll.png)

Or, you can also filter just one such as the Date as shown in the following image: 
> ![filter date](/static/images/filterDate.png)

Using any combination of these filters, you can search for a specific data that you might be curious about. 

## Summary
One drawback this website has is that we have to write the entire name of the city, or the date value etc., to their respective textbox. For example: if we just write "1/1" portion of the date instead of the entire date "1/1/2010", the data table will not get filtered and the table will be displayed empty. 
- To fix the above issue, in our app.js file, we should use the double equal "==" instead of triple equal "===" on the filter conditions and then we can have the freedom to filter without typing the entire value in the textbox. 
- Another development that can be applied to this website is that we should add the data table inside a box which can be scrollable instead of us having to scroll the entire webpage when looking through the data table. Since for our case, the data is not that many but when we have a massive array of data, we should consider using this functionality to make our website look clean.  
