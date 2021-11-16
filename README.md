CS50 Final Project - COVID-19 STATUS REPORTER website

Video Demo:  https://youtu.be/qhRHp4z8FDU

Description:

What it does?

When users visit the website their ip address is for used for locating thier country and they will be able to see covid-19 reports of thier country and any other country in the world.


How it work:

When a user go to the website from their browser(ie. chrome) to the URL(https://abdraefreq.github.io/cs50/) or www.cs50.web42.io. and he will see the current status of covid-19 in his current location or his country. if a user want to see the other country covid-19 reports he just click on change coutry in the navigation bar and select country from the list or use the input search field to easly find the country. A user can also goto the learn page from the navigation bar and learn more about covid-19 disease.

What can a visitor see?

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


THANK YOU FOR READING AND HOPE YOU WILL LOVE MY WEBSITE 

