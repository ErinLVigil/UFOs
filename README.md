# UFOs
![Screenshot 2022-10-10 165600](https://user-images.githubusercontent.com/109319148/194951148-aa1308e2-789e-4c4c-80a0-c225e1c7c4dc.png)

## Overview

We are not alone. There is ample evidence of life existing on other planets and accounts of that life visiting our planet in the form of UFOs. The sightings of these UFOs usually happen in less densly populated parts of the country and take on a wide variety of characteristics. As with any data analytics project, one of the first things to do is to identify if there are patterns in this data. By using a a large data file that already groups our sightings into key:value pairs, we can build a way to display this table and filter it by common elements. This will allow us to organize a very large data set and identify patterns and groups of filters that are similar.

### Style elements

The information and subject matter for this project is unique and fascinating. It only makes sense that we build a way to display the table that is as compelling, dynamic, and stylish as the subject matter. We've encorporated colors that look like the night sky and images to help engage our user community to use our tool.

## Results

The UFO webpage is built with a catcy title at the top followed by some text explaining the tool. 

Under this explaination is a table with information on UFO sightings and filters to enter criteria on the left hand side of the page. Entering text in these search boxes allows a user to filter down the data by specific filters.


There are many ways to approach Dana's webpage. Fundamentally, a user needs to decide what it is they want to view. This "data question" will determine how many filters we need to fill out. Let's start with a simple question: "Are there similar shapes seen in the same states?"

In order to answer this, let's first start by looking at a couple of cities. Scrolling through the data on the webpage, I can pick up a few cities that are a good starting point. I pick California, Arizona, and Colorado.

### Step 1: Enter criteria
![enter CA](https://user-images.githubusercontent.com/109319148/194952411-0e1fb7be-df9f-447a-b533-dc20b641ee00.png)

First, I enter "ca" in the Filter box for State as seen above and hit "Enter" causing the table to update with only information from California. I use "ca" because I can see in the table that State is designated by lower case abreviations. 

### Step 2: Interpret the data

While we can immediately see that the shape is described differently in the "Shape" column, the descriptions tell us something VERY INTERESTING!! There are a number of sightings on the same day in 2010 in several California cities that all describe three red lights! Something was in the sky that night!

![California results](https://user-images.githubusercontent.com/109319148/194952966-05c61212-d5b5-453c-bd65-ccf8ce57d8be.png)


### Step 3: Repeat with a different state

Inserting Arizona (az) into the criteria is not as interesting. There are only two sightings and nothing in common. 

![az](https://user-images.githubusercontent.com/109319148/194953198-fb3ad7a7-8674-4ae8-a50f-d1b593766511.png)

### Step 4: One more state, just to see how this is working

Colorado has 4 sightings spread across 3 dates. Nothing in common with these sightings either, unfortunately. 

![colorado](https://user-images.githubusercontent.com/109319148/194953434-6577b991-5e29-4aca-855c-e195cb0580fe.png)

I would continue to repeat steps such as this to narrow down where there are patterns in the data. This could be used to start further research with other data sources.


## Summary

My method above works to find patterns, but is very time consuming. One drawback to this design is that I cannot sort the columns. If I could sort all the cities together in alphabetical order, I could scroll down and identify patterns in the same city or state. This would be much easier to group the data than to just type things into the search criteria.

If I were to continue to develop this page, I would look into how to sort columns or enter multiple search criteria into the boxes. I know that some cities are very small and neighbor other cities. It would be good to look at two or three cities that are close by at once. Currently, I have to look at each one at a time or an entire state with cities that I do not need.

Another idea would be to make this data exportable in a csv file. Filtering my data is awesome, but sometimes I want to save my searches to compare data in several searches. I would need to export the data in order to do this. Some sort of export button would be great.
