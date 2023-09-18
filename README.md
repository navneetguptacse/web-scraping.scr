## Web Scraping with Flask

### **Description**

Web Scraping with Flask is a versatile web application that leverages the power of web scraping to retrieve and analyze product reviews from the popular e-commerce platform, Flipkart. This project combines the capabilities of Flask, a micro web framework, with BeautifulSoup for parsing HTML, and MongoDB for storing and managing scraped data efficiently.

### **Key Features**

- **User-Friendly Web Interface :** The project offers a user-friendly web interface for users to input their search query, making it easy to initiate the scraping process.

- **Scraping Flipkart :** The application scrapes Flipkart search results for a specified product or query, extracting valuable information such as product names, customer names, ratings, review headings, and comments.

- **Data Storage in MongoDB :** The scraped data is stored in a MongoDB database. This allows for efficient data retrieval, storage, and querying, ensuring that the data is well-organized and easily accessible.

- **Logging for Error Handling :** The project incorporates logging to track any potential errors or exceptions during the scraping process, making it easier to troubleshoot and maintain.

- **Cross-Origin Resource Sharing (CORS) :** To ensure compatibility with web browsers and prevent cross-origin issues, the application utilizes Flask-CORS for handling cross-origin requests.

- **Dynamic CSV Generation :** The application dynamically generates a CSV file containing the scraped data, enabling users to download and analyze the data offline.

### **How It Works**

- Users access the web application through their web browser.
- They input their desired product or query in the search bar and submit the form.
- The application performs web scraping on Flipkart's website to retrieve product reviews related to the query.
- The scraped data is stored in a MongoDB database for future reference and analysis.
- Users are presented with a user-friendly interface displaying the scraped reviews, including product names, customer names, ratings, review headings, and comments.
- Users can also download the scraped data in CSV format for further analysis.