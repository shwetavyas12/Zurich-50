
# GitHub Users in Zurich

This project scrapes GitHub for users located in Zurich with over 50 followers and their public repositories.

## Files
- **users.csv**: Contains information about users in Zurich.
- **repositories.csv**: Contains information about public repositories for each user.
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
