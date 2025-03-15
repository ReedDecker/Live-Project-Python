# Live-Project-Python
## Introduction - NextNest App

During my time at the Tech Academy I joined a team of developers building a suite of applications for a 2 week sprint. This was an apprenticeship done for [Prosper IT Consulting ](https://www.linkedin.com/company/prosper-it-consulting/) where I participated in Agile/Scrum practices by completing user stories (as well as sprint planning, daily stand-ups, sprint retrospective) to deliver a fully functional application on-time. I personally was tasked with creating an app that aggregates civic data to give clients more confidence when moving to a new place...

It is called ***NextNest***.

Having limited experience with Django's structure and syntax proved to be challenging at points but also rewarding. Having a heads-up attitude and solving problems in real-time gave me further confidence in my ability to overcome roadblocks and generate workable solutions. Not only did I successfully learn new material and deliver a completed product days ahead of schedule, but I gained hands-on project management and team programming skills that I know will be greatly benficial in the future.

Below are descriptions of the stories I worked on, along with code snippets, and navigation links. I also have full code files in this repo for the larger functionalities that were implemented.

## User Stories

* [Build NextNest App](#build-nextnest-app)
* [Create a City](#create-a-city)
* [Display City Data](https://github.com/ReedDecker/Live-Project-Python/blob/main/url)
* [View City Details](https://github.com/ReedDecker/Live-Project-Python/blob/main/url)
* [Edit + Delete City Info](https://github.com/ReedDecker/Live-Project-Python/blob/main/url)
* [Restful API](https://github.com/ReedDecker/Live-Project-Python/blob/main/url)
* [Parse JSON Data](https://github.com/ReedDecker/Live-Project-Python/blob/main/url)
* [Beautiful Soup](https://github.com/ReedDecker/Live-Project-Python/blob/main/url)
* [Parse HTML Data](https://github.com/ReedDecker/Live-Project-Python/blob/main/url)
* [UI / UX](https://github.com/ReedDecker/Live-Project-Python/blob/main/url)
* [Save API Results](https://github.com/ReedDecker/Live-Project-Python/blob/main/url)



## Build NextNest App

In this story I was responsible for creating a basic landing page with Navbar for the NextNest App. <br>
This would be the foundation for the layout and functionality of the application...
    
<img width="1080" alt="HomePage" src="https://github.com/user-attachments/assets/0cc108cc-f58c-4350-bfc0-7ec009afa986" />


## Create a City

For this story I created a custom form to receive input from the user and to save specific city metrics in the database. <br>
Custom classes and functions were defined as well as a model manager to facilitate the chosen city demographics.

<img width="1080" alt="CreateCity" src="https://github.com/user-attachments/assets/47bebdce-940c-461e-9928-78e2b58b9b95" />

<img width="998" alt="ModelsA" src="https://github.com/user-attachments/assets/3d5ffcb8-7f8f-4144-b00a-df7cfc5819a5" />

<img width="1009" alt="ModelsB" src="https://github.com/user-attachments/assets/5166a727-8d11-451c-92a0-f9eff9d05f53" />

<img width="938" alt="DefineCityData" src="https://github.com/user-attachments/assets/c852cfb1-1093-4abe-b2e4-06d3d7f786c4" />


## Display City Data

Here the user input is summarized into a data block that will be available in an editable table for further user customization. <br>
Examples of key demographics could be Population, Diversity Index, Median Household Income, Major Industries etc.

<img width="1797" alt="CitySummary" src="https://github.com/user-attachments/assets/ac5bbe23-5789-482e-8c47-98843403a131" />

<img width="895" alt="CreateCity_Summary" src="https://github.com/user-attachments/assets/f4ad5d63-bbe3-4e26-b840-ab35e29e0835" />



## View + Edit + Delete City Info

Once submitted, the city data is formatted into a convenient table. I created a hover-over effect so each demographic metric can be 
easily selected to then View / Edit / Delete said info based on user's desire.

<img width="1080" alt="All_Items" src="https://github.com/user-attachments/assets/4dfdf4ec-bdb1-4d49-bd90-58a16d53cca1" />

<img width="771" alt="ITEM_FORM" src="https://github.com/user-attachments/assets/74c691f8-50bb-4d4f-841a-096982ddb143" />



## Restful API - View + Filter + Save City Info

For this user story I utilized Data USA restful API to obtain civic and governmental data metrics that are verified, current and reliable. 
I parsed the JSON data from the restful API to aggregate into a user-friendly interface. <br>
User can then filter a specific demographic from the API Data and save it to a Favorites List if desired.

<img width="1843" alt="API_DATA" src="https://github.com/user-attachments/assets/51c6fbab-ff63-4a0f-90eb-45d2f9e82f98" />

<img width="910" alt="VIEW_API" src="https://github.com/user-attachments/assets/e7e90a96-1eea-4775-90ca-c7a7f0f27bb9" />

<img width="1080" alt="Favorites" src="https://github.com/user-attachments/assets/ed4cba72-1c0b-44e3-827c-58bfcbd65a4b" />

<img width="966" alt="Filter_API" src="https://github.com/user-attachments/assets/c8e9e7d1-d1e7-4c2c-a6f7-07d0d85f4616" />


## Beautiful Soup-Parse HTML Data

In this user story I employed Beautiful Soup and Selenium to scrape and parse through HTML to deliver specific demographics for a
selected city. Once the user clicks on the city, the scraper does the rest and conveniently creates a pop-up window that displays <br>
the selected city's demographic information. In this example it shows the demographic info for Los Angeles, CA.
<img width="1080" alt="ScraperLA" src="https://github.com/user-attachments/assets/b2b6634f-613a-4fe7-8f0b-7fca11deeaae" />

<img width="864" alt="Scraper" src="https://github.com/user-attachments/assets/44a276f7-2d9b-4bb1-bb04-dff0622eb0ae" />


## Contact Form

<img width="1846" alt="ContactFormPic" src="https://github.com/user-attachments/assets/59e1f665-2411-45cc-acbd-3730d1625121" />

<img width="864" alt="ContactForm" src="https://github.com/user-attachments/assets/7123edd2-65fc-459e-aa0c-47b00bb1b0c2" />













