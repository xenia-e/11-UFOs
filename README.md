# UFOs

# Overview of the project 

Adjust the current web app to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria. 
 
 
 ## Methods 
Using JavaScript,  **D3.js JavaScript library** and HTML, we modified the code in the current web app to create more table filters. Created JavaScript function  able to dynamically filter data on web application HTML page

### Data source:
- [data.js](https://github.com/xenia-e/11-UFOs/blob/main/static/js/data.js) 

## Deliverables

- __Deliverable 1:__ Filter UFO sightings on multiple criteria [app.js](https://github.com/xenia-e/11-UFOs/blob/main/static/js/app.js)
- __Deliverable 2:__ Written report on the UFO analysis ([README.md](https://github.com/xenia-e/11-UFOs/blob/main/README.md))

# Results

We created dynamic filtering of provided data using JavaScript. In addition to data filter we added filters for the city, state, country, and shape.

To use this filter you simply type in filtering criteria in the corresponding field (e.g. city 'el Cajon) and get you table filtered without reloading the page by clicking "enter" on your keyboard or switching to another filter input field (you can use tab key for that)

![user guid image 1](https://github.com/xenia-e/11-UFOs/blob/main/static/images/user_guide_1.png)

>Figure 1 - Using filter criteria

Our code provides the ability to filter data using multiple criteria. Add two or more criteria to the input filed to narrow your search

![user guid image 2](https://github.com/xenia-e/11-UFOs/blob/main/static/images/user_guide_2.png)

>Figure 2 - Using multiple filter criteria


To clear the filters and return all data to the screen simply clear the input field. 

# Summary

Even though our function works flawlessly and has its advantages compared to simple search it has its drawbacks. 

First of all the filtering criteria are not very clear and user-friendly. Typing in filters could lead to false results. To avoid that we could use the following improvements:

- use the dropdown menu to choose from the list of cities and states, which will have only those states and cities that are resent in our data.
- remove country field since we have only one (us) in order not to confuse users.
- use selection or dropdown for the shape filed. 
- add a "Clear All Filters" button whitch will allow us to clear all filters at once.
- use auto-completion tips 
- add the ability to filter not only by data but by period. 

Besides this good filtering mechanisms should also give instant feedback about the impact of our filters. This can be a simple indicator that the filters are being applied or notification if no results meet the criteria. 

