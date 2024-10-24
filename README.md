## TDS_PROJECT1
##Tools in Data Science - Project 1
## GitHub Repository Analysis

* This project scrapes data from the GitHub API to analyze public repositories of specified users.
* The analysis revealed that JavaScript is the most popular programming language among the users analyzed.  
* Developers should focus on using JavaScript and contributing to open-source projects to enhance their visibility and collaboration opportunities. 

## Data Scraping

The data was scraped using the GitHub API and the `requests` library in Python.  The script iterated through a list of GitHub users, fetched their public repositories (up to 500 most recently pushed), and extracted relevant information like repository name, creation date, stars, watchers, language, etc. This data was then stored in a CSV file for further analysis.

## Interesting Fact

The most interesting and surprising fact found during the analysis is that  majority of these developers work at	'UNIVERSITY OF TORONTO'.JAVA SCRIPT is most popular language among these users.

## Actionable Recommendation
* **Focus on JavaScript:** Given the popularity of JavaScript, developers should consider learning and using JavaScript in their projects.
* **Contribute to Open Source:** Contributing to open-source projects can increase visibility, collaboration opportunities, and skill development.

## Data Files

* `\content\drive\My Drive\users.csv`: Contains the list of GitHub users whose repositories were analyzed.
* `\content\drive\My Drive\repositories.csv`: Contains the scraped data about the repositories.
