NASA Astronomy Picture of the Day Viewer
This Flask web application allows users to view and search for images from NASA's Astronomy Picture of the Day (APOD) archive. The app scrapes images from NASA's website and displays them along with relevant information such as the date.

Features
Today's Picture: Automatically fetches and displays the most recent Astronomy Picture of the Day.
Archive Search: Allows users to search for pictures from specific dates in the APOD archive by entering a date.
Installation
Prerequisites
Python 3.7 or higher
pip (Python package installer)
Clone the Repository
<pre> <code> git clone https://github.com/OdinScriptKitty/NASA_Daily_Image </code> </pre>



<pre> <code> cd nasa-apod-viewer </code> </pre>
Install Dependencies

<pre> <code>pip install -r requirements.txt </code> </pre>




Run the Application
<pre><code>python webscrapeOnline.py</code> </pre>


**Usage**
**Viewing Today's Picture**
	Simply open the app in your web browser to view the latest Astronomy Picture of the Day.
**Searching the Archive**
	Enter a date in the YY/MM/DD format in the search form.
	Click "Search" to view the image from that specific date.

 
**File Structure**
	<pre> <code>
 	nasa-apod-viewer/
	│
	├── templates/
	│   └── home.html          # HTML template for the home page
	│
	├── webscrapeOnline.py     # Main Flask application file
	├── README.md              # This README file
	└── requirements.txt       # Python dependencies
</code> </pre>
	
 
**Dependencies**
	**Flask**: Web framework used to build the application.
	**BeautifulSoup4**: Used for parsing HTML to scrape data from NASA's website.
	**requests**: Used for making HTTP requests to retrieve web pages.
 
**Contributing**
	Contributions are welcome! Please fork the repository and submit a pull request.

**License**
	This project is licensed under the MIT License.

**Acknowledgments**
	NASA's Astronomy Picture of the Day (APOD) website for the images and data.
	You can customize this README as needed, especially if you want to add specific instructions or 
	additional details about the project.
