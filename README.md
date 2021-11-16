CS50 Final Project - COVID-19 STATUS REPORTER website

Video Demo:  https://youtu.be/qhRHp4z8FDU

Description:

What it does:

When users visit the website their ip address is for used for locating thier country and they will be able to see covid-19 reports of thier country and any other country in the world.


How it work:

When a user go to the website from their browser(ie. chrome) to the URL(https://abdraefreq.github.io/cs50/) or www.cs50.web42.io. and he will see the current status of covid-19 in his current location or his country. if a user want to see the other country covid-19 reports he just click on change coutry in the navigation bar and select country from the list or use the input search field to easly find the country. A user can also goto the learn page from the navigation bar and learn more about covid-19 disease.

What can a visitor see

- New covid-19 cases report[of the visit day] along side with the total cases report in a country
- New covid-19 recoved report[of the visit day] along side with the total recoverd patients report in a country
- New covid-19 death report[of the visit day] along side with the total death report in a country
- Learn what covid-19 is, learn about the symptom and the prevention method.


TODO THAT:

 I used a js geographic web service called geoplugin API 
("https://api.ipgeolocation.io/ipgeo?apiKey=14c7928d2aef416287e034ee91cd360d") to get geographical location(country or ISO CODE) of visitors and i created an array which is named country list in a js code to check the country code that come from geoplugin API and compare with my the one inside the array and to figure out whether the country exist or not, if the country that came from the geoplugin API exist in the array, the user country will pass to covid-19 API (https://api.covid19api.com/total/country/) and by fetching the data of current statstic of the covid-19 and the report will be presented to the user.

Technology used: 

- HTML
- CSS
- JS and CDNJS

Contents:

The website is comprised of the following contents

- 2 image: for logo, favicon and minimize sign

- 2 HTML: index.html for homepage and learn.html for learn page

- 2 CSS: style.css for page content and nav.css for navigation bar  

- 3 JS: nav.js for navigation bar responive toogle button, countries.js for function and array of countries list and app.js a main script. and cdnjs for chart.


How the geoplugin work:

First we need to the script that is given by the API to our js code and fucntions to the information or user country ISO code after getting that data we create a fuction in our java script that compare the presence of API country with the Array that we created or we must create and if its true then we can cofirm that the user country exist and we can use a fetch function to get the covid status for the API that provide the covid 19 status data.
the fetch logic include promise http response and json file and js object.

the js object is the basically the data that a user will see on screen when ever he visit the webpage or select a country from the country list. 

the js function is stored in a specific folder called js the css file stored in a folder called and the image are stored in a folder called img and the readme document is stored in a root folder.

the nav.css is used for styling the navigation bar of the page and it is called from the index page and learn page html stylesheet. 
the style.css is used for styling all the content of the website, media query is also used in the css to change the website layout based on specific pixle which is max size of 600px for navbar and 800px for page content.

the html inner elements include header, paragraphs, anchor, strong, list, span, unorderd list and breaks.

the footer section also use the same stylesheet style.css and will fallow the responsive design of the page.





THANK YOU FOR READING AND HOPE YOU WILL LOVE MY WEBSITE 

