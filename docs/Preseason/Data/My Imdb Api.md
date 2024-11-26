---
sidebar_label: 'My Imdb Api'
sidebar_position: 5
---

# My IMDB API

Welcome to the IMDB API Replacement Project! This task challenges you to create a backend API that allows users to search for movies by genre while IMDB is temporarily down.

## 🚀 Key Features
- **Genre-based Movie Search**: Filter movies by specific genres
- **CSV Data Parsing**: Read and process movie data from a provided CSV file
- **RESTful API Endpoints**: Serve movie data through multiple HTTP routes
- **JSON Response**: All routes return data in JSON format

## 📝 Task Requirements
1. **Backend Framework**: Use a lightweight web framework (recommended: Flask for Python)
2. **Port Specification**: Server must listen on port 8080
3. **Routes Implementation**:
   - GET on `/`: Filter movies by genre using query parameter
   - GET on `/action`: Serve only action movies
   - GET on `/adventure`: Serve only adventure movies
   - GET on `/comedy`: Serve only comedy movies
   - GET on `/drama`: Serve only drama movies
   - GET on `/romance`: Serve only romance movies
4. **Data Source**: Parse the provided CSV file (no database required)
5. **Response Format**: All routes must return JSON-formatted responses
6. **Accessibility**: Server should be accessible at `http://web-XXXXXXXXX.docode.YYYY.qwasar.io`

## ⚙️ How the Program Works
- **Data Processing**:
  - Read the CSV file containing movie information
  - Parse the file and create an in-memory data structure
  - Filter movies based on requested genre
- **Route Handling**:
  - Root route (`/`) accepts a `genre` query parameter
  - Genre-specific routes return movies matching that genre
  - Multiple genres in a movie are supported (comma-separated)

## ⚠️ Error Handling
- Handle cases where no movies match the requested genre
- Provide appropriate error messages for invalid genre requests
- Ensure robust parsing of CSV file with potential variations

## 🛠️ Useful Resources for Accomplishing this Task
### Websites/Documentation
- [Flask Documentation](https://flask.palletsprojects.com/)
- [Python CSV Parsing](https://docs.python.org/3/library/csv.html)
- [RESTful API Design Best Practices](https://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)

### Exercise-Specific Tips
- Use `papaparse` or Python's `csv` module for CSV parsing
- Implement case-insensitive genre matching
- Consider using list comprehensions for efficient movie filtering
- Add logging to track API usage and potential issues
- Include a README.md with installation and running instructions

### Example Curl Commands
```bash
# Search by genre using query parameter
curl "http://localhost:8080?genre=action"

# Direct genre route
curl "http://localhost:8080/western"
```

### Sample Project Structure
```
my_imdb_api/
│
├── movies.csv         # Provided movie data file
├── app.py             # Main Flask application
├── README.md          # Project documentation
└── requirements.txt   # Python dependencies (only if necessary)
```

