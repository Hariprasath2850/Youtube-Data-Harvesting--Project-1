# Youtube-Data-Harvesting--Project-1
Hello There,
So excited to share my project on "Youtube data harvesitng", here I have used two different technology to webpage using streamlit. To know more about the the project please check out the procudure below!
The goal of this project is to create a Streamlit application which allows users to examine data from several YouTube channels. To access information such as video details, user engagement, and channel metadata, users must provide their YouTube channel ID. Users should be able to gather data from up to ten different channels and the app should make it easier to save the data in a MongoDB database. It should also provide the ability to move specific channel data from the data lake to a SQL database for additional examination. The application should allow for advanced features including joining tables for detailed channel information, as well as searching and retrieving data from the SQL database.

Technology Stack Used

**Python MySQL MongoDB Google Client Library**

Approach

Start by setting up a Streamlit application using the python library "streamlit", which provides an easy-to-use interface for users to enter a YouTube channel ID, view channel details, and select channels to migrate. Establish a connection to the YouTube API V3, which allows me to retrieve channel and video data by utilizing the Google API client library for Python. Store the retrieved data in a MongoDB data lake, as MongoDB is a suitable choice for handling unstructured and semi-structured data. This is done by firstly writing a method to retrieve the previously called api call and storing the same data in the database in 3 different collections. Transferring the collected data from multiple channels namely the channels,videos and comments to a SQL data warehouse, utilizing a SQL database like MySQL or PostgreSQL for this purpose. Utilize SQL queries to join tables within the SQL data warehouse and retrieve specific channel data based on user input. For that the SQL table previously made has to be properly given the the foreign and the primary key. The retrieved data is displayed within the Streamlit application, leveraging Streamlit's data visualization capabilities to create charts and graphs for users to analyze the data.
