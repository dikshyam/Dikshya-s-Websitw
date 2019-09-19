---
title: Teradata Data Challenge 2019
summary: An example of using the in-built project page.
tags:
- Classical ML Problems
date: "2019-05-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by The Wall Street Journal
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: More on GitHub
  link: https://github.com/dikshyam/Teradata-Challenge
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
**Executive Summary**: 

*Business Problem Statement*

The United States is home to a significant number of military families, comprising of veterans, active-duty service members, spouses, and dependents. They are known to possess unique skill sets, experiences and leadership abilities, despite which, many struggle to find jobs and maintain these positions for long periods of time. The facts show that active services consist of 1,358,193, i.e., 0.4% of the US population. This works out to be the third largest active military army in the world as of 2018.
As per our research and understanding, the military equips their personnel in skill sets which are helpful to qualify for up to 962 civilian occupations. However, in spite of such training the veteran unemployment rate as of 2019 is estimated at 3.7%. This represents 6.26% of the US population from 2019. On a macro level, these ill-managed unemployment rates can lead to massive debts, homelessness, health risks and infertility for veterans and military spouses and can affect the civilian market with untimely demand and retention issues.
In an attempt to help rectify this problem, we intend to support Hire Heroes in accomplishing their mission by determining the relationship between a client’s demographic profile, amount of time spent working with individual clients(time to complete an assessment, time to complete resume, # of logged activities, etc.)  and the time required for the veterans to get hired.

*Business Goal*

Hire Heroes USA, a non-profit organization is trying to empower U.S. military members, veterans and military spouses by helping them succeed in the civilian workforce. Our business goal is to help HHUSA in its primary function by building a prediction model and identifying the most critical factors that are influencing a veteran to get hired. 

*Data Profile*

The dataset was provided by Hire Heroes USA which uses Salesforce as their CRM. Out of the 13 datasets provided, we chose to use 3 datasets - Contacts (Demographic information of the client), Activities (activities the client participated in), and Hire Information. Hired/Not Hired was one of our derived variables; where 1 meant client was hired within 180 days and 0 meant client was not hired within 180 days.

*Results*

For our results, we utilized Rstudio, data integration, analysis, and modeling. Tableau and Excel were used for exploratory analysis and visualizations. On a high level, our results using Random Forest classifier has provided the best results after several levels of tuning. Due to the imbalance in data for the target variable, AUC was used as the measure for validating the performance and the final model has given 0.929 with accuracy 86.75%. In addition, we also used the survival analysis to understand the importance and significance of assigning specialists who were in charge of helping the clients through the hiring process.

