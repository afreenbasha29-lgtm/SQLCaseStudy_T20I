# T20I Cricket Analytics using MySQL
A MySQL-based cricket analytics project that analyzes T20 International matches from 2024 using SQL queries, CTEs, joins, aggregate functions and window functions to generate insights on team performance, winning percentages, head-to-head records, match statistics and tournament trends.

## Database

**Database Name:** T20ICRICKET

**Table:** T20I

### Attributes

* Team1
* Team2
* Winner
* Margin
* MatchDate
* Ground

## SQL Concepts Used

* SELECT Statements
* Filtering with WHERE
* Aggregate Functions (COUNT, AVG)
* GROUP BY and ORDER BY
* Common Table Expressions (CTEs)
* Window Functions (ROW_NUMBER, DENSE_RANK, RANK)
* Joins
* Date Functions
* Subqueries
* String Pattern Matching

## Analysis Performed

### 1. Match Results Between Two Teams

Identify all matches played between two selected teams during 2024 and display the results.

### 2. Team with Highest Wins

Determine the team that won the highest number of matches in 2024.

### 3. Team Rankings

Rank teams based on their total number of wins using window functions.

### 4. Average Winning Margin

Calculate the average winning margin for each team and identify the team with the highest average margin.

### 5. Matches Above Average Margin

List matches whose winning margin exceeded the overall average winning margin.

### 6. Most Successful Chasing Team

Find the team with the highest number of victories while chasing a target (wins by wickets).

### 7. Head-to-Head Analysis

Compare the performance of two selected teams by counting wins against each other.

### 8. Monthly Match Analysis

Identify the month in 2024 during which the highest number of T20 matches were played.

### 9. Winning Percentage Analysis

Calculate matches played, matches won, and winning percentage for each team.

### 10. Ground-wise Performance

Identify the most successful teams at different cricket grounds based on total wins.

## Learning Outcomes

Through this project, the following SQL concepts were practiced:

* Data aggregation and summarization
* Window functions and ranking
* Multi-table logic using CTEs
* Sports data analysis using SQL
* Performance metric calculation
* Query optimization and analytical reporting

## Technologies Used

* MySQL Workbench

## Author

Afreen S
