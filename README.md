# Android Data Privacy Study
## About The Project
This GitHub repository contains research on the impact of personal data permissions on user experience in smartphone apps, focusing on Android platforms. 
The project explores how permissions influence user satisfaction and competitive advantage in the app market. 
It includes two primary studies: one examining the correlation between personal data permissions and user experience in dating apps, and another analyzing the effect of Google's policy changes on app permissions and user ratings. 
The findings challenge common assumptions about data collection and user experience in app development. This research contributes to a deeper understanding of user privacy, data permissions, and their implications in the app industry.

### Built With
[![Python 3.11](https://img.shields.io/badge/Python-3.11-3776AB)](https://www.python.org/downloads/)
## Project Structure
```angular2html
├───data
├───notebooks
│   ├───statistical models
│   ├───exploratary data analysis
```
### data
This folder does not contain the scraped playstore data since the files are too big to upload.
It does contain the manual enrichment of the permissions with description, grouping, etc.
For this manual labour, different sources have been used:
- https://developer.android.com/reference/android/Manifest.permission_group
- https://gist.github.com/Watsonboy1989/fa01a6869d82062c770e137107693744#permissionandroidpermissionwrite_external_storage
- https://android.izzysoft.de/applists/perms?lang=en#:~:text=Starting%20with%20Android%2010%2C%20an,use%20it%20to%20download%20files

### notebooks
- **Statistical models:** This directory contains the notebooks that have been created to test our hypotheses. It contains two notebooks:
  - 1_ols_data_permissions_dating contains the code for Study 1, where used Ordinary Least Squares (OLS) to predict app ratings, focusing on permissions accessing personal data.
  - 2_did_restricted_permissions contains the code for Study 2, where we examine the impact of Google’s policy change in 2018, which prohibited certain permissions, using a difference-in-differences (DiD) framework.
- **Exploratory data analysis:** This directory contains the notebooks that have been created at the beginning of the project to perform initial data exploration and to develop our research questions and its hypotheses.

## Authors
- Andy Huang
- Roman Nekrasov
- Maxime Lambregts
- Huub van de Voort 
- Oumaima Lemhour
- Tom Teurlings