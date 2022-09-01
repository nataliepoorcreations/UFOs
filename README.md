# UFOs


# Overview


Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, I added table filters for the city, state, country, and shape. 

* Deliverable 1: Filter UFO sightings on multiple criteria
* Deliverable 2: A written report on the UFO analysis


# Resources

* Data Source: ufo_starterCode.js and index.html
* Data Tools: ECMAScript, JavaScript, Jupyter Notebook, Python and MongoDB
* Software: ES6+, ECMAScript, MongoDB, Python 3.9.12, Visual Studio Code 1.69.2 


# Results
## UFO Sightings html

<img width="1435" alt="webpage screen shot" src="https://user-images.githubusercontent.com/106033535/187095735-10936092-49af-49e1-a2c2-05e0186bc4ae.png">


## Filters
Using JavaScript and HTML, I modified the code in the index.html file to create more table filters. In addition to the date filter I initially created in this module, I added filters for the city, state, country, and shape, as shown in the following image:

<img width="360" alt="filters" src="https://user-images.githubusercontent.com/106033535/187095830-1b361841-e3e0-4d9d-a35e-2f3d6c20ca55.png">


Using JavaScript, I replaced the handleClick() function in the app.js file with a new function that saves the element, value, and id of the filter that was changed. Then, I created a new function to loop through the dataset and keep only the results that match the search criteria. The webpage will be updated with the search criteria after pressing "Enter".

## Results after using filters


<img width="831" alt="webpage with filters" src="https://user-images.githubusercontent.com/106033535/187095894-9fd30ae8-d716-496c-aa29-3673738afeba.png">



# Summary

## One drawback of this webpage
The user must know specific dates, cities, or shapes to search. The filters require correct lower-case spellings and cannot include spaces at the end. The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon". The only acceptable input would be "el cajon".

## Two additional recommendations for further development 
* I recomend that the filter functions be updated to a trim function to allow upper and lower case letters as well as catch spaces at the end of a word. 
* My second recomendation is that the date filter could be by month or year rather than a specific date. Without having specific dates the results won't always be there. 
