# UFOs
## Project Overview
In this repository, we will use Javascript to create a table that organizes UFO data that is stored as a JavaScript array, or list. This table will have the ability to filter data based on certain criteria and will be created using JavaScript as the primary coding language. The purpose of this analysis is to create a webpage that will allow users to search for UFO Sightings data.

## Results
The webpage created is a display of UFO sighting data with a filter table that allows users to easily filter on various criteria such as date, city, state, and shape of the UFO sighting. An unfiltered view can be seen below:
![image1.png](https://github.com/jipelletier/UFOs/blob/main/UFOs/image1.png)

The tables update in real time so there is no need to refresh. Filter selection can be broad such as only selecting a country and state like the United States and New York as shown below:
![filter1.png](https://github.com/jipelletier/UFOs/blob/main/filter1.png)

To narrow the results, you could add in the shape or date filter:
![filter2.png](https://github.com/jipelletier/UFOs/blob/main/filter2.png)

## Summary
The main advantage to our webpage is that users can search on multiple criterea at once without the need of a submit button. However, there are also some drawbacks. The draw backs are centered around the search options lack of illuding to options to search on. The current fields need exact info in order to produce results. This could allow for user error and misinterpretation making the data analysis ineffective.

### Drawbacks

- The filter method is case sensitive. Therefore if a user entered any items in upper case, the search results would not return properly. For example, a state must be lowercased in order to return results. Typing in "CA" will return nothing but "ca" will.
- The user may not know exactly what time period the data is from or runs through, so the user might type in dates that we don't have access to. 
- The Shape field doesnt specify shape options and without knowing what the shape options are, the user will not know what terms to search for.

### Reccomendations
- Remove case-sensitivity in all the textbox search fields.
- Implementing a calandar view might help instead of textbox field for the Date search.
- Add a drop down menu for the Shape field. This would be more user friendly as a drop down option than the textbox.
