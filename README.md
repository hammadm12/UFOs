# UFO Sightings
utilizing JavaScript and filters to create tables based on UFO Sighting

## Overview
Throughout the module, we helped Diana establish filters on finding specific UFO sighting dates. The tool we created were performing as intended but Diana observed that providing more filtering criteria options, it would help provide users a more in-depth UFO sightings analysis. Such new filters proposed would be adding table filters for the city, state, country and shape.

## Results
After we make changes to the Javascript, we can see the filters displayed at the left side of the page. By utilzing these filters, the data would have been displayed entirely which would have been jarring to the user as they visit the website for the first time. Since we were only searching UFO sightings with dates, it only limited the large dataset by one criteria which did help in finding certain sightings but did not help in specifying where exactly the sighting was spotted. We can now narrow down the dataset by cities, states, countries and the shape of the apparent UFO.

![]

As we can observe in the above screenshot, we are now able to specify UFO sightings based on the new filters we added to the Filter Search. Now users are able to fulfil their interests as they search sightings out of curiosity and/ or prjects.

## Summary

The new app we created with the additional search filters provides to be more efficient in analyzing the dataset given but it is not without its drawbacks.

## Drawback
One major drawback is that our starting datatbase is comparitively small, thus allowing for faster searches within the appropriate criteria but over time as the database grows with more and more UFO sightings, it can lead to server congestion since the filtered search rebuilds the data set everytime a search is performed. This can take up valuable resources from a development side in the sense the websites cache is constantly being bloated and that with more data being added, more filters may have to be created to allow for searches to become more streamlined.

## Recommendations
There are ways to improve the app created.

1. Since the filtered table is constantly being recreated with each search thus leading to the cache being congested, we can implement ways to allow for cached searches that would clear the cache evertime a new search is performed.
2. For convenience, we can also implement drop down menues to the filtered search to help users search by places they may not know the spelling to help streamline the experience for them.
