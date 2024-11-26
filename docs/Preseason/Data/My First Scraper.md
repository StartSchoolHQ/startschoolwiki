---
sidebar_label: 'My First Scraper'
sidebar_position: 4
---

# My First Scraper

> Using python libraries requests and beautifulsoup4, return a CSV of the TOP 25 trending repositories from Github.
>
>    Request (with request)
>    Extract (with beautifulsoup4)
>    Transform
>    Format


> Part 0: Request
> Write a function prototyped: def request_github_trending(url) it will return the result of Request.
>
> Part 1: Extract
> Write a function prototyped: def extract(page) to find_all instances of HTML code of repository rows and return it. You should use BeautifulSoup. :-)
>
> Part 2: Transform
> Write a function prototyped: def transform(html_repos) taking an array of all the instances of HTML code of the repository row.
> It will return an array of hash following this format: [{'developer': NAME, 'repository_name': REPOS_NAME, 'nbr_stars': NBR_STARS}, ...]
>
> Part 3: Format
> Write a function prototyped: def format(repositories_data) taking a repository array of hash and transforming it and returning it into a CSV string. Each column will be separated by , 
> and each line by \n
> The columns will be Developer,Repository Name,Number of Stars

## 🚀 Key Features

- **Request**: Use code to retrieve the raw HTML.
- **Extract**: Returns only the parts from the html useful for the transform
- **Transform**: From the useful html, get the information required to make the {'developer': NAME, 'repository_name': REPOS_NAME, 'nbr_stars': NBR_STARS} dictionary for each entry.
- **Format**: Returns the dictionary as a comma separated value (csv) string. 

## Notes
- This is a group project of two. Collaborate to solve it.
- Finding the correct token to search the html with is key to not get stuck in parsing hell. Spend some time looking at and analyzing the web page (or use some tools).
- BeautifulSoup does not always return the object you wish for (like strings in HTML). Sometimes you need to parse them manually, but try to avoid it if possible.
- For csv formatting, using json is useful to avoid gandalf disliking the formatting. 
- This task repeats in the Season 2 Data Science track.

## 📝 Game Rules/Task Requirements (Gandalf test requirements)

The returned type from each function is important for gandalf tests. The return types are:
- request_github_trending - `<class 'requests.models.Response'>`
- extract - `<class 'bs4.element.ResultSet'>`
- transform - []
- format - string

1. **Test 1**: Checks if request returns proper type
2. **Test 2**: Checks if extract returns proper type
2. **Test 3**: Checks the values and formatting of the list (and the dictionaries). Some people noted having issues with gandalf using old data
2. **Test 4**: Opens two files named 'blah2' & 'blah3'

## ⚙️ How the Program Works (Only if a project, not for quests or exercises)


## ⚠️ Error Handling

- Simple try-except wrap for the file reading


## 🛠️ Useful resources for accomplishing this task
* Beautiful soup documentation: [Beautiful soup](https://beautiful-soup-4.readthedocs.io/en/latest/)
* Github Trending page: [Github Trending](https://github.com/trending)