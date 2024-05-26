import all the required libraries.
# Process Flow
Obtain YouTube API credentials: Visit the Google Cloud Console.

Create a new project or select an existing project.

Enable the YouTube Data API v3 for your project.

Create API credentials for youtube API v3.

# ETL Process
Extracting Data from youtube API.

Transforming data into the required format.

Loading Data into SQL

# Application Flow
Select Data Retrieval and Processing Page from dropdown menu at the sidebar.

Input the Channel Id and click on Get Channel Statistics in order to retrive data from Youtube API.

click Migrate to SQLite3 to store the data

Select a channel name from the dropdown Channel Details and click on Push to SQL to import data into SQLite3.

Once imported, you can select the Analysis and Reports Page from the drop down to get a detailed analysis of the collected data.

# Additional Information
Please note that when using this application, it is essential to comply with the YouTube Data API's terms of service and adhere to its usage limits to ensure uninterrupted access to the API. If you encounter any issues or have questions regarding the YouTube Data Scraper, please refer to the project's detailed documentation available in the GitHub repository.
