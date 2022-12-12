# National-Park-Project
My Nashville Software School Capstone

## Table of contents
* [Executive Summary](#executive-summary)
* [Motivation](#motivation)
* [Data Questions](#data-questions)
* [Data Sources](#data-sources)
* [Technologies Used](#technologies-used)
* [Known Issues and Challenges](#known-issues-and-challenges)

## Executive Summary
The U.S. is home to 63 national parks, and I want to provide an analysis on the key factors that make them great. The parks are beautiful, but they can also be treacherous. While visiting the parks is relatively safe, I want to look at how and how many deaths occur in the parks. The parks can be dangerous for humans, but they are sanctuaries for animals. Viewing wildlife is one of the main reasons people visit the parks, and I want to find out what role endangered species play in drawing visitors. I will look at the national parks from the perspective of “humans in danger…and animals endangered.”

## Motivation
I have always loved national parks, and it’s my goal to visit all of them! National parks have a few layers of interest for me. When I visited the Grand Canyon, my aunt brought a book titled Over the Edge: Death in the Grand Canyon. Now every time I see a headline article about a death in a national park, I must read it! Another factor that draws me to national parks is the wildlife. When I went to Yellowstone National Park, I was in awe over the majestic bison roaming the fields. I found out that in the late 1880’s bison were near extinction. National parks are home to many animals that are an endangered species, and the parks play a big role in protecting them.

## Data Questions
Which national parks average the most visitors? How (and how often) do people die in the national parks? Is there a correlation between the most popular parks and the parks with the most deaths? Is there a correlation between a park’s popularity the endangered animals it is home to?

## Data Sources
 * National Park Service: [Visitor Stats](https://irma.nps.gov/STATS/Reports/Home)

 * Deaths in the national parks: [Data Downloads](https://www.nps.gov/aboutus/foia/foia-frd.htm)

* Endangered species: [Data Downloads](https://esa.npca.org/)

* Facts about the 63 national parks: a combination of webscraping from [Wikipedia](https://en.wikipedia.org/wiki/List_of_national_parks_of_the_United_States) and merging with an existing dataset from [Kaggle](https://www.kaggle.com/datasets/nationalparkservice/park-biodiversity?select=parks.csv)

## Technologies Used
* Python
* Jupyter Notebooks
* Excel
* Tableau

## Known Issues and Challenges
The U.S. has 63 national parks, which is what I want to focus on. I know I’ll have to filter the data to return results for the title "National Park," because there are also national monuments, national forests, preservations, seashores, etc.

There are many nuances in the way parks are spelled and punctuated, i.e "&" vs. "and." A good example is "Gates of the Arctic National Park." There are extra spaces in that park name throughout some of my tables, so I'm going back through and making sure all the park names are a perfect match, so I can merge the tables and use "Park Name" as my primary key. 
