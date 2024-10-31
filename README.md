-Data scraped using GitHub API for users in Delhi with over 100 followers and their repositories.
-After analyzing, the most surprising insight was the diversity of languages used even in a single user’s repositories.
-Developers can consider adding diverse tech stacks and documentation to attract more collaborators.

Overview
This project leverages the GitHub API to gather data about GitHub users located in Delhi who have more than 100 followers, along with details of their repositories. The purpose of this data collection is to gain insights into the professional profiles, projects, and preferences of developers in this region. Notably, the analysis revealed interesting trends, including the types of licenses most frequently used and the profiles of the earliest GitHub adopters from Delhi. Based on the findings, actionable insights are provided for developers aiming to improve their profiles and projects on GitHub.

Project Structure
The project contains several key files:

users.csv: This file stores information about GitHub users from Delhi who have at least 100 followers.
repositories.csv: This file contains data on up to 500 of the most recent repositories for each user listed in users.csv.
gitscrap.py: This Python script automates the data collection process using the GitHub API, with data cleaning functions that standardize certain fields.
README.md: Project documentation, including setup instructions, data descriptions, and usage guidance.

Based on the data collected, developers in Delhi can draw inspiration from popular languages and licensing choices, explore high-traffic repositories, and consider strategies for increasing engagement metrics like followers and stars on GitHub.

