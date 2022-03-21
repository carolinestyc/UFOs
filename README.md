# UFOs
  Challenge 11

## Project Overview
Dana is creating a webpage about UFO's - one of her favorite subjects. After a synopsis on UFO sightings, the webpage features a filterable table that pulls data on sightings. Using html and JavaScript, I helped her create the webpage and pull in the data. Initially, she requested the table be filterable by date and now she wants a more in-depth analysis. She requested I add filters for city, state, country, and shape. Asking for user input and allowing the user to pull more data that fits their criteria. Below is walk through of the functionality of the webpage.

### Resources
            Data Sources: data.js
            
            Software: VS Code, JavaScript, html, css
            
## Results
### Opening the Webpage
The main purpose of the webpage is to filter data by the users' preferred criteria but it of course starts with bit more information. As the webpage loads up you see the header behind an image of Earth's atmosphere.

<img width="1259" alt="Header" src="https://user-images.githubusercontent.com/96352625/159202406-4c03294c-a827-44d7-8fe5-acf79c9cc1fa.png">

As the user scrolls, they come to a brief 4 paragraph write-up on UFO sightings being fact or fiction before the dive into their search.

<img width="1267" alt="Fact_or_Fiction" src="https://user-images.githubusercontent.com/96352625/159202415-7132aba6-9bf7-4ae8-89ad-90c9c2bed98a.png">

### Filtering the Data
When the search function is blank, the webpage shows every point of data, and the filter fields are blank besides for the example searches. Having suggested searches shows the user what type of syntax to use while searching. For example, the data is in lower case so the user must search using lower case. Additionally, the state and country variables use short hand; United States is us and California is ca. Therefore, the user needs to apply the same case when searching.

<img width="1259" alt="table_unfiltered" src="https://user-images.githubusercontent.com/96352625/159202425-4288a9b2-4c57-41f1-851f-88f26851f2ef.png">

Now, the user can search based on their preferred criteria. For example, if they want to see all the UFO sightings in the state of Arizona, they will type "az" into the Enter State field and press "enter", pulling up all sightings in the state of Arizona. As shown below, there are 2 sightings in the state of Arizona.

<img width="1179" alt="state_filter" src="https://user-images.githubusercontent.com/96352625/159202750-e26dea77-84dd-4838-b746-6b254257928e.png">

## Summary
Dana and I have built a great webpage that satisfies her request: the user can filter the UFO sightings based on a few different criteria. However, there are still a few ways to improve the site and there is a drawback to its currently functionality. That being, the search is case sensitive. As discussed earlier, the user must utilize the suggested case in the search fields to draw an accurate search. If they were to search AZ or Arizona instead or az, the search would pull 0 sightings in Arizona but that would be inacurate. 

And there are a few of ways to improve the website for future development. First, when searching for the shape, the user may not know what words are searchable. There are many shapes to the sightings, "fireball" being one that the user may not even know about. Therefore, instead of a search option, I would suggest a drop down menu or a list of the different options and the user can select one or many to see the list of complete options. Additionally, I would also suggest adding different functionality to the date search field. The current structure requires a month/day/year format so you can't search for the whole month. I would allow for the user to search for 1/2010 to pull up the whole month of January 2010 as well the current function of 1/1/2010. This will allow for even better data filtering. And finally, I would include a results counter; showing the user how many results are populated based on their chosen criteria.
