# B.Sc Colleges Data Scraping from CollegeDunia

## Table of Contents
1. [Introduction](#introduction)
2. [Project Objective](#project-objective)
3. [Technologies Used](#technologies-used)
4. [Data Collected](#data-collected)
5. [Challenges](#challenges)
6. [Methodology](#methodology)
7. [Conclusion](#conclusion)

---

## Introduction
This project focuses on web scraping to gather information on B.Sc colleges from [CollegeDunia.com](https://collegedunia.com). The data collected includes details such as college name, location, accreditation, ranking, courses offered, fees, reviews, and ratings. This data aims to support analysis on trends in B.Sc course offerings and college performance.

## Project Objective
The objective of this project was to gather comprehensive data on B.Sc colleges to analyze trends related to college rankings, course availability, and tuition fees.

## Technologies Used
- **Python**: Primary programming language for this project.
- **Selenium**: For automating browser interactions and handling dynamic content.
- **BeautifulSoup**: For parsing HTML and extracting relevant data fields.

## Data Collected
The following fields were extracted for each college:
- **College Name**
- **Location**
- **Accreditation**
- **CD Rank**
- **Courses Offered**
- **B.Sc Fees**
- **Reviews**
- **Rating**
- **URL**

## Challenges
1. **Page Load Time**: Loading a large number of colleges (4945) increased the page load time.
2. **Dynamic Content Handling**: Some elements were loaded dynamically, requiring careful handling with Selenium to ensure all data was fully rendered before extraction.

## Methodology
### Steps to Scrape Data
1. **Setting Up the Environment**: Install necessary libraries and set up Selenium WebDriver.
2. **Web Navigation**: Use Selenium to navigate to CollegeDunia and find B.Sc course listings.
3. **Data Extraction**: Use BeautifulSoup to parse HTML and extract required information.
4. **Data Storage**: Save the extracted data to a structured format like CSV for analysis.

## Conclusion
This project successfully extracted detailed information on B.Sc colleges from CollegeDunia.com. Despite challenges such as load times and dynamic content, using Selenium and BeautifulSoup provided a reliable way to capture relevant data for analysis.




