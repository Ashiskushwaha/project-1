- This project uses the GitHub API to gather and analyze user data from Austin with over 100 followers, focusing on profile and repository details.
- An interesting finding was that the top developers in Austin frequently use JavaScript, with most being affiliated with well-known tech companies.
- Recommendation: Developers should prioritize updating project details like bios and licensing to attract more followers.

# Austin GitHub User and Repository Analysis

## Project Overview
This project involves scraping GitHub data for users in Austin with over 100 followers and analyzing various aspects of their profiles and repositories. We created two CSV files, `users.csv` and `repositories.csv`, and analyzed the results based on factors like language popularity, company affiliations, and activity metrics.

### Files Included
- **users.csv**: Details of Austin users with 100+ followers, containing GitHub user data such as bio, company, and follower stats.
- **repositories.csv**: Information on public repositories of users in `users.csv`, listing language, license, and activity data.
- **README.md**: This file, documenting the project, findings, and methods.

### Process Summary
1. **Data Collection**: Using GitHub's API, we fetched Austin users with 100+ followers and parsed their profile and repository data.
2. **Data Cleaning**: Company names were standardized by trimming whitespace, removing initial '@' symbols, and converting to uppercase.
3. **Data Storage**: Data was stored in CSV files in the main branch of this repository.

### Findings and Insights
- **Top Companies**: Many Austin developers are associated with large companies like Google and IBM.
- **Popular Languages**: JavaScript and HTML are the top languages among Austin developers.
- **License Types**: MIT and Apache-2.0 licenses are commonly used.

### Recommendations for Developers
- Optimize repository settings (projects, wikis) to enhance visibility.
- Clearly document repositories and maintain updated profiles to increase follower engagement.
- Consider licensing open-source projects to improve collaborative potential.

### Analysis Highlights
- **Followers and Repositories Correlation**: Low correlation (0.150), suggesting repository count alone doesn’t predict follower growth.
- **Language Preference**: Fennel has a high average star count, indicating niche popularity.
- **Leader Strength Calculation**: Top Austin users demonstrate strong follower networks relative to those they follow.


