## UFOs
Using Javascript, bootstrap to make a UFO sightings page

## Overview of the Project
For this project we are building an HTML page that will allow us to pull up information from a javascript data file using filters on the page. We want to use filters since we have many different sightings.We have customized the webpage using Bootstrap, and equiped the table with several fully functional filters that will allow users to interact with our visualizations.

### Aim
The aim of this project is to create an interactive webpage that allows readers to parse the data around UFO sightings. 

## Results
Using JavaScript and HTML we have created an interactive webpage that allows the reader to parse the data around UFO sightings. As we can see in Fig.1 below, the user can search the data by filtering based on:

* Date
* City
* State
* Country
* Shape

![ss1](https://user-images.githubusercontent.com/111541268/201548200-2b625aa6-d952-4b35-a1b8-3bd7844daefd.png)

Once entering the website our client will see the basic opening and title with the picture at the top, as the client scrolls down they will begin to see all the data and filters that we have(which is in the image below). From this image below we have 5 different filters to choose from; the date, city, state, country & shape. You can choose any of these filters enter the search bar, then the HTML page will show all of the sightings for that specific search. Multiple filters can be entered at the same time to further inspect the data in the specific search bar that is entered.




When a user wants to see data for the date 1/13/2010 for example, they must write this value in the first filter field. As we can see in Fig. below, 3 sightings were recorded in that date.



Users may enter as many filters as wanted together and empty the filter boxes that they don’t in order to parse the data around UFO sightings.


## Summary
Despite being visually appealing and dynamic, this design present one important drawback. Each time, users want to start a new selection criteria, one must go through all the input fields to delete the previous search criteria. This could take a lot of time and could easily annoy the user. I would suggest adding a "clear filters" button that would empty all input fields by one click. Moreover, in order to make the code shorter and faster, I would suggest refactoring the code by deleting filterTable() function and merging it with updateFilters() function.
