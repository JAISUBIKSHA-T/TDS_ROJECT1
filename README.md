## TDS_PROJECT1
##Tools in Data Science - Project 1
## GitHub Repository Analysis

* This project scrapes data from the GitHub API to analyze public repositories of all users in the city of 'Toronto' with over 100 followers.
* THe data is stored in 'users.csv' and 'repositories.csv'.
* I learned a new concept of creating GitHubToken and giving authorization to it.
* Diiferent types of queires used in the program.
* I learned to use THreadPoolExecutor to handle multiple threads at a time.


## Data Scraping

The data was scraped using the GitHub API and the `requests` library in Python.  The script iterated through a list of GitHub users, fetched their public repositories (up to 500 most recently pushed), and extracted relevant information like repository name, creation date, stars, watchers, language, etc. This data was then stored in a CSV file for further analysis.

## Interesting Fact

The most interesting and surprising fact found during the analysis is that earliest repository is created at 2008. I didnt went to my playschool at that time. And the majority of these developers work at	'UNIVERSITY OF TORONTO'.JAVA SCRIPT is most popular language among these users.

## Actionable Recommendation
* **Focus on JavaScript:** Given the popularity of JavaScript, developers should consider learning and using JavaScript in their projects.
* **Contribute to Open Source:** Contributing to open-source projects can increase visibility, collaboration opportunities, and skill development.

## Data Files
users.csv : https://drive.google.com/file/d/1hQeJ5INpuUrRcHjiAoypv4Uuu-GE639o/view?usp=drive_link  
repositories.csv : https://drive.google.com/file/d/1-WUcdfDnLHA8pdMenOuZcSCW1nKlaIyg/view?usp=drive_link        

Collect_data.ipynp: https://colab.research.google.com/drive/15r8O8-cbcok7i_FSXecqGBnooLgvJ02u?usp=drive_link


