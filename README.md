# Spotify-Analysis
This project analyzes spotify data to deliver insights for stakeholders. Spotify offers 100M+ songs and 7M podcasts, with featureslike personalization and social sharing

## Project Background
Spotify is a digital music, podcast, and video service that provides access to millions of songs, podcasts, and other audio content. Spotify is available on a wide range of devices, including computers, phones, tablets, and smart speakers. Daniel Ek is our founder, Chief Executive Officer, and Chairman of our board of directors. As our Chief Executive Officer and Chairman, Mr. Ek is responsible for guiding the vision and strategy of the Company and leading the management team. Spotify boasts a vast library of over 100 million songs and 7 million podcasts. The platform uses algorithms and user data to suggest music and podcasts tailored to individual preferences. Spotify allows users to follow friends, create and share playlists, and even host listening parties called "Jams". In this project we have to analyse the data and provide insights to the stakeholders for the kery requirements provided by the company.
## Steps in Project
- Requirement Gathering / Business Requirements.
- Data Walkthrough.
- Data Cleaning / Quality Check.
- Data Modeling.
- Data Processing
- DAX Calculations.
- Dashboard Lay outing.
- Charts Development and Formatting.
- Dashboard / Report Development.
- Insights Generation.
## Project Overview & Objective
In today's digital music era, understanding listening patterns is crucial for both users and streaming platforms. This analysis focuses on spotify albums data, providing insights into user engagement with albums over time.
### Albums
- Total Albumd Played Over Time -  Track how album listening trends change over months and years.
- Number of Albums Listened by Year - Identify annual listening habits and volume.
- Albums Played on Weekday & Weekend - Identify the pattern of music listening on weekdays and weekends.
- Top 5 Albums - Identify the most palyed albums based on listening frequency.
- Latest Year vs Previous Year Analysis - Compare album consumption between the latest and previuo years, including:
  1) LY (Latest Year) vs PY (Previous Year) Trends.
  2) YoY (Year-over-Year) Growth Analysis.
### Artists
- Total Artists Played Over Time - Track how artist listening trends evolve across months and years.
- Number of Artists Listened by Year - Identify annual listening habits and artist diversity.
- Artists Played on Weekday & Weekend - Identify the pattern of music listening on weekdays and weekends.
- Top 5 Artists - Identify the most played artist based on listening frequency.
- Latest Year vs Previous Year Analysis - Comapare artsit engagement between the latest and previous years, including:
  1) LY (Latest Year) vs PY (Previous Year) Trends.
  2) YoY (Year-over-Year) Growth Analysis.
### Tracks
- Total Tracks Played Over Time - Monitor how track listening trends change across months and years.
- Number of tracks Listened by Year - Identify annual listening habits and tracks diversity.
- Tracks Played on Weekday & Weekend - Identify the pattern of music listening on weekdays and weekends.
- Top 5 Tracks - Identify the most played tracks based on listening frquency.
- Latest Year vs Previous Year Analysis - Compare track engagement between the latest and previous years, including:
  1) LY(Latest Year) vs PY(Previous Year) Trends.
  2) YoY(Year-over-Year) Growth Analysis.
 ### Listening Patterns
 - Listening Hours Analysis - Identify peak listening times using a Heat Map that visualizes patterns across hours and days with color intensity.
 - Average Listening Time(min) vs Track Frequency - Use a Scatter Plot eith Quadrant Analysis to categorize tracks based on:
   1) High Frequency & High Listening Time - Most engaging tracks.
   2) Low Frequecy & High Time - Niche but impactful tracks.
   3) High Frequency & Low Listening Time - Short & frequently played tracks.
   4) Low Frequency & Low Listening Time  - Less popular tracks.
### Details Grid
In this report, The aim is to analyse the data by creating an interactive and dynamic grid view. The grid will display key details such as Album Name, Artist Name, Track Name, and other relevant attributes.

Key Requirements:
- Grid View with Essential Fields:
  1) The Grid should present critical data points for an intuitive and structured view.
- Drill Through Functionality:
  1) Users should be able to drill through from the main  reports to explore underlying data for detailed insights.
  2) The drilled-through data should be exportable to a CSV file based on user requirements.
- Drill Down, Drill Up, and Hierarchy:
  1) The grid should support hierarchical navigation, allowing users to drill down and up for in-depth data exploration.

## Executive Summary
### Overview of Findings
As per the data, Spotify played 7383 albums with 3835 artists and 12724 tracks over time. The app is mostly played on weekends as compared to weekdays. It's latest year vs previous year trend is decreasing as it is in negative, and the top album played is " The Beatles". This is all the summary of first dashboard and in second dashboard as per the requirement is a heat map showing the listening hours which is less in day time and more in night time. Also plotted a quadrant plot for average listening time and track frequency. The image of the dashboard are below, and in depth insights are given in next part.
### Dashboard 1:
![image](https://github.com/user-attachments/assets/f810d9c3-4dd9-423b-ac70-915a19d67aa0)
### Dashboard 2:
![image](https://github.com/user-attachments/assets/e96d086b-4dc4-4360-a467-b73562871203)
### Dashboard 3:
![image](https://github.com/user-attachments/assets/c97d72e4-dbd9-4a95-a16e-89e39b198d8e)

## Findings & Insights
After analysing the data of Spotify we got required insights from it, which are listed below as per the business requirements mentioned for the data. Focusing on user engagement with albums and it increased over time.
### Albums
- Afetr tracking album trends overall, we got that albums played over time is 7097.
- As per analysis minimum albums played overall platforms was in 2014 (Number of albums: 22) and maximmum albums played was in 2021 (Number of albums: 2668).
- Analysis tells pattern of music listening on weekdays is more than weekends i.e. weekdays 6435(63.08%) and in weekends 3766(36.92%).
- Based on listening frequency most played 5 albums are The Beatles, Post Masters, Abbey road, The Wall, Revolver.
- Album consumption between the latest and previous years, including:
  1) There is overall decline in consumption of albums as LY: 1824 & PY: 2333.
  2) Album consumption growth is declined by 21.82%.
### Artists
- Artist listening trends across years evolves have increased gradually, 4112 artist played over time.
- As per analysis annual listening habits diversity is increased consistently, minimum no. of artist are 21(in 2014) and maximum no. of artist are 3578(in 2021).
- Pattern of music listening of different artist on weekdays is 3393(63.15%) and weekends is 1980(36.85%).
- The most played artists based on listening frequency are The Beatles, THe Killers, John Maver, Bob Dylan, Paul McCartney.
- By the analysis of artist engagement between the latest and previous years, including:
  1) Shows that artist engagement is declared a little as LY: 1071 & PY: 1455.
  2) Analysis shows that growth of artist year over year is declined by 26.39%.
### Tracks
- As per the analysis, track listening trends in years engagement increased significantly. Over time the total played were 12724.
- Annual listening habits diversity after reviewing the data gave insight of minimum traxks played over time was 23 in 2014 and maximum was 5106 in 2021.
- The pattern of music listening on weekdays is 11714(64.26%) and weekends is 6516(35.74%).
- The 5 most played tracks based on listening frequency are Ode to the Mets, Inth Blood, Dying Breed, Coution, 19 Dias y 500 Noches.
- Track engagement between the latest and previous years, including:
  1) Engagement between LY and PY is decreased significantly as LY: 3568 & PY: 4031.
  2) Analysis shows that engagement of track year over year is declined by 31.49%.
### Listening Patterns
- After analysing peak listening times using a Heat Map that visualizes patterns across hours and days with color intensity, we got that mostly on Friday and Saturday night is peak time.
- Least listening hours in days is in morning from 9am t0 afternoon 1pm. Rest of the time is we have constant engagement of listening.
