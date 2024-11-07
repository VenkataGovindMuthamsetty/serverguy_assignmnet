![Screenshot (17)](https://github.com/user-attachments/assets/a8a84bc3-009c-4b29-9800-9a86b1067e70)

# Algolia Hacker News Search Clone
This project is a React-based clone of the Algolia Hacker News search interface. It allows users to search for stories, comments, or polls from Hacker News, filter results by popularity or date, and narrow down searches based on time ranges. Users can navigate through paginated results and view individual story details.

# Features
Search Functionality: Allows users to search for stories, comments, or polls by title, URL, or author.

# Filtering:
-> Story Type: Filter by stories, comments, or polls. -> Sort Order: Sort results by popularity or date. -> Time Range: Filter results by time ranges such as "Last 24 hours," "Past week," "Past month," and "Past year." -> Pagination: Navigate through multiple pages of search results. -> Responsive Design: Adapts to different screen sizes for a seamless experience on both desktop and mobile devices.

# Key Components
=> Header: Displays the title and a placeholder login link. => SearchBar: Provides filters and a search input field for querying stories. => ResultItem: Displays individual search results. => Pagination: Allows users to move between pages of search results.

# Setup
Prerequisites Node.js: Make sure Node.js is installed on your machine. npm or yarn: This project uses npm by default, but you can use yarn as well.

# Installation
Clone the repository: -> git clone [https://github.com/ChetanPalade/serverguy_chehackernews_assignment.git]

-> cd hackernews_clone

# Install dependencies:
---- npm install

# Start the development server:
---- npm start

=> Open the app in your browser: Navigate to http://localhost:3000.

# Usage
Use the search input and filters to find specific stories, comments, or polls. Navigate through paginated results using the "Previous" and "Next" buttons at the bottom of the page.

# Integration with Algolia Hacker News API
Currently, this project uses mock data for demonstration. To integrate it with the actual Algolia Hacker News API, replace the handleSearch function in Home.js with an API call as follows:

javascript
import axios from 'axios';

const handleSearch = async (query, storyType, sortOrder, timeRange) => { const response = await axios.get(https://hn.algolia.com/api/v1/search?query=${query}&tags=${storyType}&numericFilters=${timeRange}&sortOrder=${sortOrder}); setResults(response.data.hits); }; Make sure to update the API parameters as needed.

# Folder Structure
src/components: Contains reusable components like Header, SearchBar, ResultItem, and Pagination. src/pages: Contains the main Home page where all components are brought together. src/App.js: Main application file that renders the Home component. src/index.js: Entry point that renders the React app.

# Dependencies
React: UI library for building the interface. Axios (optional): For making API calls to the Algolia Hacker News API (if integrated).

# Screenshots
Include screenshots here showing the search page, filters, and pagination. Screenshot (1) Screenshot (2)Screenshot (8) Screenshot (3)

![U![Screenshot (26)](https://github.com/user-attachments/assets/6c3a1cd1-2611-4812-bfe1-23e08ec05f4d)
![Screenshot (25)](https://github.com/user-attachments/assets/32310581-66ac-455f-bf88-260604b46e4e)
![Screenshot (24)](https://github.com/user-attachments/assets/c9008747-8a59-4626-a42d-f068a48707c6)
![S![Screenshot (27)](https://github.com/user-attachments/assets/5a28c703-817a-43e8-82be-27d53c8261b7)
![Screenshot (26)](https://github.com/user-attachments/assets/c3edb958-eb73-4c44-818e-0bb5dca1b70d)
![Screenshot (25)](https://github.com/user-attachments/assets/040e1508-48bd-4d6e-9e4e-5cda1e9b4c96)
creenshot (23)](https://github.com/user-attachments/assets/52d98b13-d670-4252-829a-50e7a6df2b6c)
![Screenshot (22)](https://github.com/user-attachments/assets/93bb1a39-c9d3-4171-a461-777fc9d73a81)
![Screenshot (21)](https://github.com/user-attachments/assets/e165e39d-e3fd-485c-b42a-867a389f391f)
![Screenshot (20)](![Screenshot (27)](https://github.com/user-attachments/assets/9aecd347-ff65-4892-878a-677296e61a84)
https://github.com/user-attachments/assets/5774b4e8-5976-45b5-81a2-0b8a0b8bdd87)
![Screenshot (19)](https://github.com/user-attachments/assets/7c00644b-552f-46b8-b0d0-a9b77c760b32)
![Screenshot (18)](https://github.com/user-attachments/assets/57ee5e62-31fe-4af7-8426-db24d56d600e)


Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.
