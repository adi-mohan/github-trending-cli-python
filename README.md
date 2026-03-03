# github-trending-cli-python
CLI application that talks to GitHub API and shows the trending repositories

The CLI tool will fetch data from the GitHub API and present it in a user-friendly format. The tool should be easy to use and provide clear output.

Language: Pick any backend language

GitHub API: Utilize the GitHub REST API for fetching repository data.

Authentication: No authentication required for public repositories.

Time Range Options: Support filtering by day, week, month, and year.

Data Fetching: Implement error handling for API requests.

Data Parsing: Parse the JSON response from the GitHub API.

Sorting: Sort repositories by star count.

Output Formatting: Display the trending repositories in a clear and readable format (e.g., repository name, description, number of stars, language).

Command-Line Arguments:

--duration: Specifies the time i.e. day, week, month, year). Default to week.

--limit: Specifies the number of repositories to display. Default to 10.

Error Handling: Implement robust error handling for invalid input and API errors.

Documentation: Provide clear instructions on how to install and use the tool.

Example Usage: trending-repos --duration month --limit 20

Link: https://roadmap.sh/projects/github-trending-cli
