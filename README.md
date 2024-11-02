
# GitHub Users in Zurich
This project scrapes GitHub for users located in Zurich with over 50 followers and their public repositories.

 
1. This project analyzes GitHub users in Zurich with over 50 followers, using the GitHub API for data collection. We utilized Python's requests library to extract user profiles and repository details, examining factors like follower count, hiring status, and repository features. Data was stored in CSV files for analysis.

2. Key Findings: Users with more repositories attract more followers, hireable developers tend to share their email addresses, and enabling both projects and wikis enhances collaboration and documentation.

3. Recommendations for Developers: Create and share more public repositories to attract followers, enable wikis and project boards for better collaboration, and provide contact information to facilitate networking for job opportunities.

## Files
- **users.csv**: Contains information about users in Zurich.
- **repositories.csv**: Contains information about public repositories for each user.
- **TDSProject1.ipynb**: Python code file used to scrap the data.
- **TDSProject1-Solutions.ipynb**: Project Solutions using Python code.
- **README.md**: This file.


## User Fields
- **login**: User GitHub ID
- **name**: Full name
- **company**: Company they work at
- **location**: City they are in
- **email**: Email address
- **hireable**: Whether they are open to being hired
- **bio**: Short bio
- **public_repos**: Number of public repositories
- **followers**: Number of followers
- **following**: Number of people they are following
- **created_at**: When they joined GitHub

## Repository Fields
- **login**: User GitHub ID
- **full_name**: Full name of the repository
- **created_at**: When the repository was created
- **stargazers_count**: Number of stars
- **watchers_count**: Number of watchers
- **language**: Programming language
- **has_projects**: Whether the repository has projects enabled
- **has_wiki**: Whether the repository has a wiki
- **license_name**: License type
