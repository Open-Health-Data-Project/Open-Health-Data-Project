# Open Health Data Project
Our goal is to enable people to privately collect and analyze data about their physical and mental health to improve their quality of life. \
To achieve this, we propose to create an ecosystem consisting of a mobile, a desktop, and a web app connected together by a private server (localhost) and a public server that will store the data that users have chosen to share.

## Proposed architecture

<img src="https://github.com/Open-Health-Data-Project/Open-Health-Data-Project/blob/main/images/architecture.png" width="500">

## Data flow

<img src="https://github.com/Open-Health-Data-Project/Open-Health-Data-Project/blob/main/images/data-flow.png" width="720">

## Data categories

<img src="https://github.com/Open-Health-Data-Project/Open-Health-Data-Project/blob/main/images/collected-data.png" width="720">


## Problems to be solved by the project:
* Controlling your time (time management)
* Checking how actions you are taking relate to your plan or general health standards (e.g., recommended sleep time, activities, recommended nutrient intake, alcohol intake, time spent in front of the computer, etc.)
* Receive recommendations based on current data
* Derive general indicators from the data - for example, health condition index, healthy eating index, activity index - to compare your results with others in a more anonymous way
* Motivate yourself to study/work by setting a daily/monthly time target for these activities
* More efficient use of time at work
* Recommendations based on the music you listen to
* Receive interesting facts about yourself - e.g., your vocabulary, predicted personality type, animation of how your appearance changes over time, etc
* Possibility of private data collection and processing
* Control over your data - which data to share and which to keep private

## Technological solutions
### Health Data Tracker mobile app solutions
* Integration of user data from various sources: applications, services, databases, files, APIs
* Creating a simple data entry interface that supports recording certain data at the same time and the limitations associated with it, e.g. you can listen to music and walk at the same time, but you cannot swim and do cycling simultaneously
* Ensuring consistency and standardization of collected data through data consistency checking functions
* Unifying data collected automatically and manually by the user - data goes to the same tables in the database and in the same format
* Where possible, use automatic data logging - using the device's sensors
* Make it possible to collect any features over time - users can define the key and type of value themselves
* Control over data - possibility of correcting historical data
* Recording time, numerical, textual and graphic data in one application - storing data in SQL database and files
* Flexible application data structures - expandable as needed in the future
* Use localhost API to exchange data between mobile and desktop application and same API on server to send data to shared database
* Three levels of data privacy: on phone, local network, public
* Scope of collected data depends on the user

### Health Data Tracker & Analyzer desktop application solutions
* Synchronizes data with Health Data Tracker
* Works also in offline mode
* Various data summaries, dashboards
* Various data visualizations
* Comparison of current data with recommendations of WHO and other institutions
* Optionally with publicly available data of other users
* Possibility of electronic time recording

### Solutions within the Health Data Network web application
* Providing an API for uploading public user data to the server
* Machine learning models trained on the data provided
* Comparative visualizations with other users
* Advanced predictions and suggestions based on data processed by models

## Benefits
* Enable simple collection and processing of your data
* Get recommendations based on your existing data
* Reducing bad habits

## Contributing to Open Health Data Project

If you want to join to our organization or you have any questions contact us on e-mail: openhdp@gmail.com
