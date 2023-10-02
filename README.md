# YouTube-Data-Warehousing-and-Harvesting

📊 A comprehensive solution for collecting, storing, and analyzing YouTube data.

## Overview

This repository houses the codebase and documentation for our YouTube Data Warehousing and Harvesting project. Our mission is to help you harness the wealth of information available on YouTube by providing a powerful framework for data collection and storage.


## Key Features
- 📈 **Data Harvesting**: Effortlessly gather video metadata, comments, and statistics from YouTube channels and videos.
- 📦 **Data Warehousing**: Store collected data in a structured and scalable data warehouse for easy access and analysis.
- 📊 **Data Analysis**: Perform in-depth analysis, generate insights, and visualize trends using your YouTube data.
- 🌐 **Multi-platform**: Supports integration with popular data analytics tools, ensuring seamless workflow.

**Additional Features**:

- 📡 **YouTube Channel Integration**: Input a YouTube channel ID and retrieve all relevant data (Channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, comments of each video) using the Google API.
- 🗄️ **MongoDB Integration**: Option to store the data in a MongoDB database as a collection.
- 📊 **Multi-channel Support**: Ability to collect data for up to 10 different YouTube channels and store them in a MongoDB Database collection.
- 🔄 **Database Migration**: Option to migrate the data from MongoDB Database to a SQL database as tables.
- 🔍 **Advanced Search**: Ability to search and retrieve data from the SQL database using different search options, including joining tables to get channel details.



## Python Libraries

### googleapiclient
- **Description:** The `googleapiclient` library is used to interact with Google APIs, such as the YouTube Data API, for data harvesting from YouTube channels and videos.

### pymongo
- **Description:** `pymongo` is a Python driver for MongoDB, allowing you to connect to and interact with MongoDB databases. In this project, it is used for storing and retrieving data from MongoDB collections.

### pandas
- **Description:** `pandas` is a powerful data manipulation and analysis library. It's used for data processing, cleaning, and transformation, making it an essential part of our data warehousing and analysis workflow.

### mysql.connector
- **Description:** `mysql.connector` is a library for connecting to MySQL databases. In your project, it's used for migrating data from MongoDB to a SQL database and managing SQL data.

### streamlit
- **Description:** `streamlit` is a framework for creating web applications with Python. It's used to build a user-friendly interface for interacting with and visualizing the data collected and stored in your project.

These libraries play crucial roles in the development of our YouTube Data Warehousing and Harvesting project, enabling various data-related tasks, from data retrieval and storage to analysis and user interaction.

## Skills Learned 

- Python scripting
- Data Collection in MongoDB and SQL
- Streamlit
- API integration
- Data Management using MongoDB (Atlas) and MySQL



## Workflow and Execution of the Project
### Project Workflow and Execution

### Data Harvesting from YouTube Data API:
1. Access the [Google Cloud Console](https://console.cloud.google.com) to manage Google Cloud services.
2. Create a new project in the console.
3. Enable the YouTube Data API v3 for your project.
4. Generate an API Key for authentication.
5. Visit [YouTube Data API documentation](https://developers.google.com/youtube/v3/docs) for reference codes.
6. Utilize the `googleapiclient` library to interact with the YouTube Data API.
7. Initialize a connection to the YouTube Data API using your API Key.
8. Implement code to extract required details.

### Storing Data in MongoDB Atlas Database:
1. MongoDB Atlas is a cloud-based platform for MongoDB database management.
2. Create an account in MongoDB Atlas.
3. Create a cluster, project, database, and collections in MongoDB Atlas.
4. Set up a connection to your MongoDB database using the connection string.
5. Use the `pymongo` library to interact with MongoDB.
6. Store the extracted data in MongoDB for further processing and analysis.

### Fetching Data from MongoDB and Creating a DataFrame:
1. Establish a connection to the MongoDB database.
2. Query the MongoDB collections to retrieve desired data.
3. Convert the retrieved data into a pandas DataFrame.

### Migrating Data to SQL for Structuring:
1. Set up a connection to an SQL database (e.g., MySQL, PostgreSQL.
2. Create necessary tables to represent the desired data structure.
3. Migrate data from the DataFrame to the SQL database, populating tables with structured data.

### Answering Predefined Questions using SQL Commands:
1. Utilize SQL queries to extract required information from the SQL database.
2. Present the required information in a structured format.

### Creating and Displaying Data in a Web Application:
1. Use Streamlit to build a data visualization and analysis web application.
2. Display the retrieved data in the Streamlit app.
3. Implement user-friendly features such as entering a YouTube channel ID, viewing channel details, and selecting channels for migration.
4. Create buttons for each task, with each button appearing after the execution of the prior button.

This workflow outlines the steps involved in the project, from data harvesting and storage to analysis and web application development.




