# Dataset-Analyzation-Project
## Authors:
- Scott Bader
- Frances Hollan
- Katie Kaffenbarger
- Joe Erste

A repo project for Project 1 of the OSU Bootcamp.

# Scope
## The effects of economic events and circumstances on the housing market.

# Data Topics
- median household incomes
- median home sales prices
- average hourly employee earnings
- personal income
- 30yr & 15yr fixed mortgage rates
- employment to population ratio
- home ownership rate
- rate of inflation

# Dependencies
- `time`
- `dotenv`
- `os`
- `datapackage`
- `pandas`
- `json`

# Overview
Below is an overview of the project and it's many parts and aspects.

## Communication
Slack was our primary communication method due to using it for the bootcamp for the past few months. It was easy to use and everyone knew how to use it well so it was a very easy and unspoken choice.
Our slack channel was where we communicated times, goals, topics, and pinning important information for later use.
![Slack Logo Image](https://1000logos.net/wp-content/uploads/2021/06/Slack-logo.png)

## Development Process
Our process involved using feature-branching and pull & merge requests to make sure that only the best code was merged into `main` branch.
The process went as follows:
### Example of a coder updating the app with their changes:
1. `git checkout -b [BRANCH-NAME]` - This will create a new branch and the terminal will switch to that branch all in one line.
2. `git add` - Add your changes.
3. `git commit` - Commit and write a commit message to detail the changes.
4. `git push --set-upstream origin [BRANCH-NAME]` - Push the committed changes to the repo and set the upstream branch to your current branch.
5. **Create a pull request**
6. **Await approval**
7. **Merge the branch with the main branch**

## Data Gathering
Our data was gathered from the FRED (Federal Reserve Economic Data) provieded by the [Federal Reserve Bank of St. Louis](https://fred.stlouisfed.org).
It was downloaded in `.csv` file format.
We also used the CPI ([Consumer Price Index](https://www.bls.gov/cpi/)) API from the U.S. Bureau of Labor Statistics to determine inflation and adjust our graphs.

## Visualization Process
A variety of styles were used to visualize our data. The main two forms of graphs that were used were **scatter plot graphs** and **line graphs**.
![Median Sales Price of Housing vs. Median Household Income Scatter Plot Graph](https://github.com/ManWithACap/Dataset-Analyzation-Project/assets/58278360/3d93391f-234b-48d1-a9c3-06aaca01eb2d)
![Comparison of Economic Indicators of Home Sales Over Time (1984 - 2014) Line Graph](https://github.com/ManWithACap/Dataset-Analyzation-Project/assets/58278360/b394d5a8-ebc5-4776-8fbc-0e3d811d3377)
![30-year Fixed Rate Mortgage Average vs. Multiple Rates and Indexes](https://github.com/ManWithACap/Dataset-Analyzation-Project/assets/58278360/e2fc757f-dcc1-4bef-9754-2f17d9904d02)


## Conclusion
Based on the data analyzed, we can conclude that outside events such as housing crises like the one in 2008 and the events leading up to them in previous years can and almost certainly will affect even the housing market
aside from just income averages and employment. It is not a far-off thought that world events can influence consumers and businesses.

# Installation
1. Navigate to the [Releases](https://github.com/ManWithACap/Dataset-Analyzation-Project/releases) page in the repository.
2. In the latest release, click on the topmost `.zip` file in the assets drop-down menu. **This will begin a download for that file.**
3. Navigate to the folder (on your computer) where the file was downloaded to.
4. Select and right click the file.
5. Click the "Extract to ..." option in the pop-up context menu.
6. Confirm and await the file to extract itself.
7. Once it has finished, you are now free to navigate into the newly created folder. Congrats! You've successfully installed the files!

# [Google Slides Presentation](https://docs.google.com/presentation/d/1iXeSSd6Rq4a-cJEMqTeJVu8s1xzzOzvBpfKv-EWBuMg/edit?usp=sharing)
