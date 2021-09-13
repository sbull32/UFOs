# UFOs_
Module 11

## Overview
The purpose of the analysis done was to create a user friendly way of searching through numerous ufo sightings compiled together on our data.js file. In order to do this we needed to create a script which would build the table data we would put on the webpage and then allow a user to filter through these sightings by either date, state, city, country, or vehicle shape.  By adding numerous list elements to our html file we built these search options which take in user input and update the table on the page to only show the relevant information requested by the user.

## Results

We created a webpage using js and html scripts as well as css styling elements to create our data tables for users to review. In order to update the page we needed to create 4 more filter classes so the user will be able to search by their defined criteria. below is the coding we came up with to create these filters.

![html_filters](https://github.com/sbull32/UFOs_/blob/main/html_filters_classes.png)

We then adjusted our event listener to listen to a change in the selected inputs as opposed to the button click we had previously used. Below is the final webpage for users to access with the filters city, state, country, date, and shape for the user to input.

![ufo_filters](https://github.com/sbull32/UFOs_/blob/main/ufofilters.png)

Once an input is entered, the user can hit enter on their keyboard in order to update the table with the desired filtered values.

## Summary

One drawback of this webpage is that the data we are using is static and not dynamic, meaning all of the data the table is pulling up was manually entered in a dataset and doesn't allow for new sightings to be added to our search.

One suggestion to improve the webpage would be to link our data to an API of somesort which contains similar data to the data we used for this webpage, however it can be updated as time moves forward. This would allow a user to view new sightings which would be preferrable for a long term solution to our problem. Another suggestion might be to include a button instead of the updated version which changes when a user hits enter after inputting their desired filter value. I just prefer the button aesthetics and believe it gives the user a feeling of more control when entering in their desired filter values.

