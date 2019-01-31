![picture](http://d.up-00.com/2019/01/154826204517681.jpg)
***
## UX

this project, I needed to build a data dashboard that visualizes a dataset of my choice.
Datasets can be found all over the web but are not always reliable  presented interestingly.
In this case, I decided to pick a Whiskey subject and present it as simply, playfully as possible

### <a href="https://albeeralkhawri.github.io/Whiskey-Collection/"> *Whiskey-Collection* </a>

## Features
- Page by page presentation of content for a better user experience (using pagePiling.js)
- Charts created using d3.js, dc.js and crossfilter
- Interactive filtering of data reflected in a datatable
   > The datatable clearly displays the information available and offers an external link to the associated Google Search for more details 
- Revolving quotes and information snippets at the top of the page
- Disclaimer page
- pictures

## Functionality of the project 
I incorporated links and buttons to allow my user to navigate the site, along with an easier control of the site functionality.

I endeavoured to make the site is as responsive as possible, however I realised that the best user experience with charts necessitated a bigger screen than most smartphones. Charts using D3.js are not responsive as they are designed for desktop or large-screen viewing. I tested this by checking the site on different screen sizes and browsers. 

My chart containers are responsive however and will be displayed differently at the medium and large breaking points. Again, charts using D3.js are not responsive as they are designed for desktop or large-screen viewing.

To ensure visitors would not miss out, I included a message to invite visitors back to the site using a bigger viewport.


## Process
 I wrote down user stories and created a wireframe before embarking on full-blown development.

## The webpage's mockup
* v1. [Wireframe here!](./dashboard.png)
* v2. Updated [wireframe](./dashboard_v2.png) for powerpoint-like presentation

## Technologies used 
 Since my single-page application makes use of Bootstrap (a CSS frameworks) and other libraries, I created a vendor file to ensure a clear separation between the library code and my own code.
 
 - HTML5
 - CSS3
  
- [Bootstrap v.4.1](https://getbootstrap.com/)  
   > Bootstrap is an open source toolkit for developing with HTML, CSS, and JS.                         

- [pagePiling](https://alvarotrigo.com/pagePiling/)
  > JQuery plugin to create beautiful scrollable websites
- jQuery
  > jQuery is a cross-platform JavaScript library designed to simplify the client-side scripting of HTML.
- Data-specific Javascript libraries
  - [D3.js](https://d3js.org)
  - [DC.js](https://dc-js.github.io/dc.js)
  - [Crossfilter](https://square.github.io/crossfilter)
  > *D3.js* is a JavaScript library for manipulating documents based on data. *dc.js* is a javascript charting library with native crossfilter support, allowing highly efficient exploration on large multi-dimensional datasets (inspired by crossfilter's demo). It leverages d3 to render charts in CSS-friendly 
  - queue
  >*d3-queue* is a tiny library for running asynchronous tasks with configurable concurrency.


I used Git & GitHub for version control. Each new piece of functionality should be in a separate commit; I proceeded with that in mind, although a bit clumsily in retrospect. I will create branches for future commits and subsquent projects!

The final version of my code is hosted on GitHub Pages.
The project live here: https://github.com/albeeralkhawri/Whiskey-Collection


## Testing

To the best of my abilitities, I conducted and documented tests to ensure that all of my website's functionality work well.


1. Access and filter data on the webpage
   
    I. Upon access to the webpage, the second section of the webpage indicates where to find filters and how to navigate the site. The possible ways to filter the charts are through the collapsible menu (via hamburger icon), by resetting all filters at once using the double arrow icon at the top-left corner of the screen or by clicking on the charts directly.
    
    II.  The top-left hamburger menu reveals once clicked three diffent ways to filter the results. A note informs the visitor that the window can be closed following his/her choice.
    
    III. Use of the 'search' input filters the data vailable by country. If country is mispelled or does not correspond to the available data, the charts remain blank.

    IV. An error message is displayed in the filter menu and in the datatable section for a few seconds if a visitor types in something that does not match the data available. This message invites the visitor to make another attempt.
    
    V.  Use of the drop-down menu allows for the selection of a specific a Whiskey a time. If data is already filtered, the available choices are limited.
    
    VI. The 'reset all filters' button allows for all filters to be removed at once. The same option is available at the top-left corner of the screen when the menu is closed and at the datatable section.

    VII. Regardless of where the filters are chosen, there is no issue in selecting a filter by clicking on a chart and then accessing the menu for further filtering.  
    

2. Charts
   
    I. The piecharts have a limited amount of slices displayed to simplify the data presented. 

    II. The color palette used on all charts allows for an easier read of each element.The barchart displays multiple labels to allow for an easier view of the data available or filtered.

    III.  Clicking on a slice of the piechart or on the barchart affects all other charts available on the webpage.

    IV. Additional filtering is not possible through the datatable. The datatable displays the data available (and/or filtered) allowing a view of 5 elements maximum at once. This is set up to prevent too much information to be displayed, leading to the confusion of the viewer.

    V. The datatable is paginated to permit access further data. Pagination is disabled if no further data can be displayed.


3. Responsiveness of the webpage
   
    I. The webpage has been tested on various devices and screen sizes. I requested inputs from friends and family members using a variety of devices to ensure an equal viewing experience. Browserling [(link here)](https://www.browserling.com/) was also used review browser compatibility.
    
    II. A message is displayed when screen size deemed too small for a proper view of the dashboard. This message invites the viewer to return to the page using a larger sized screen.

    III. The chart containers are responsive even if the charts themselves are not. The charts have been separated in different sections for a less 'crowded' or overwelming user experience (since the webpage appeals to adults). The charts will also be displayed differently following the medium and large breaking points of to the viewport.

4. Redirection to external pages
   
    I. Links on the webpage are set up so that they open in a separate window. The user can keep their current view of the webpage in parallel. 
    
    II. Links are easily identified through the usage of button elements or highlights in a different color. For instance, the links within the datatable are orange buttons with the value 'Learn more'. 

5. Communication
   
    I. An introductory paragraph has been included at the top of the webpage to go through the purpose of the page and the interaction possible with its elements.
    
    II. A direct reference to the webmaster's email is provided at the bottom of the webpage (footer section), along with a reference in the disclaimer modal.
 
## Deployment 

This project was deployed through the Github pages.
It can be download or cloned using the relevant Github option at the top-right of the project page. 

The project is live here: https://github.com/albeeralkhawri/Whiskey-Collection

  
## Credits and Content

This information has also been included (in fewer words) in the disclaimer portion of the webpage.
                              
- [Disclaimer Generator](https://disclaimergenerator.net#wizard)
  > I added a disclaimer page as the data used for the purposes of the project, while quite detailed, might be incorrect, incomplete or repetitive. I did my best to tailor and rectify certain details
- Data 
   >My data has been imported from [here](https://github.com/gabyguedezh/whiskey-insights/blob/master/assets/data/whiskey-insight.csv) and you have filtered and edited it and added picture it manually.
- [Google fonts Open Courgette & Kalam ](https://fonts.google.com/?selection.family=Courgette|Kalam) 
   > The webpage's fanciful fonts can be found, along with many other great fonts, in Google's own collection.    
- [Bootstrap v.4.1](https://getbootstrap.com/)  
                                    

## Contact

Feel free to get in touch for feedback.

<a href="https://mail.google.com/mail/u/0/#inbox?compose=new">**alberhabib1993@gmail.com**</a>
