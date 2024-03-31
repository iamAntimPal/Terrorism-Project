# Global Terrorism Analysis
## intern Career Task 2

## Table of Content

- [Project Overview](project-overview)
- [Data Sources](data-sources)
- [Tools](tools)
- [Data Cleaning/ Preparation](data-cleaning/-preparation)
- [Exploratory Data Analysis](exploratory-data-analysis)
- [Data Analysis](data-analysis)
- [Results](results)
- [Recommendations](recommendations)
- [Limitations](limitations)
- [References](references)

### 📌 Project Overview

This Data Analysis project attempts to provide information about global terrorism. I look further into the terrorism dataset, which contains a wide range of information covering 1970 to 2017. My primary goal is to do a thorough data analysis, deleting missing values, outliers, and extraneous columns to maintain the integrity and high quality of my report.

### 📚 Data Sources

Global Terrorism Data: The key dataset utilized in this research is the "Terrorism.csv" file, which contains information such as the country and region where the terrorist attack occurred, the type of weapon used, and so on. 

[Access the File Here](https://drive.google.com/drive/u/1/folders/1aQqtP9-OX3BwX-olp1vD0Zq9NYBKvtJu)

### 🧰 Tools

- Power BI
  - [Download Here](https://www.microsoft.com/en-us/download/details.aspx?id=58494)
- Microsoft PowerPoint
  - [Download Here](https://www.microsoft.com/en-za/microsoft-365/powerpoint)

### 🧹 Data Cleaning/ Preparation

In the intial phase of my data preparation, I performed the following tasks:

- Data loading into Power BI.
- Cleaned (Transform Data) my dataset in PowerQuery.
- Data formatting

### 👓 Exploratory Data Analysis

This step of the analysis involve answering key questions:

- Are data types correctly assigned?
- What are trends in attack types and weapons used?
- How do the casualties vary by year in each country?

### 📊 Data Analysis

1. Initially, the "Terrorism.csv" dataset file contained 135 columns and 181 691 rows, and I had to delete all extraneous columns for analysis, as well as all rows with missing data. After the data cleaning I was only left with 9 rows for my data analysis.

<img src="Assets\csv_file.png">


2. I then looked at the top six types of attacks, weapons, and targets based on success rate.

<img src="Assets\power2.png">

3. I also investigated the top six countries with the highest casualties/success rate, and visualized countries affected by terrorism on a map with bubble sizes denoting the success rate; the larger the bubble, the more affected the country is by terrorism. I then visualized the success rate of terrorism by region. 
<img src="Assets\power3.png">

4. The Taliban, a terrorist group, came first on the list of terrorist groups that have carried out numerous attacks. It was necessary to look at the total number of terrorist strikes worldwide in order to comprehend how much has changed over time.

<img src="Assets\power4.png">

5. Laslty I designed a slicer to visualize the most dangerous group, total targets, maximum number of attacks per year, and most commonly used weapon for each country and region.

<img src="Assets\power1.png">

### ⚖️ Results

- From 1970 to 2017 terrorism increased from 647 to 10743 total attacks, with 2014 having the highest total attacks of 16694.
- Bombing/ Explosion is the most common type of attack with a success rate of 48.62%.
- Private Citizens & Property rank number 1 on the most common target type followed by the Military on number 2.
- The Middle East & North Africa region have the highest success rate.
- The top 3 countries with the most terrorist attacks are Iraq, Pakistan and Afghanistan.
- Taliban is the most dangerous group with 11964 total targets and explosives being their mostly used weapon.

### 📖 Recommendations

1. Improve Data Collection:

The larger the sample size, the higher the report's quality and the accuracy of the findings. As a result, the dataset should contain few or no unknown or missing values.

2. Invest in Cutting-Edge Technology:

Investigate and invest in technological innovations like advanced analytics and machine learning algorithms to detect patterns, trends, and potential outliers in data. These technologies can help you derive valuable insights even from vast and complex datasets. These technoligies are less likely to make mistakes or miss any important details.

### ⏳ Limitations

The presence of missing or unknown variables in a terrorism dataset significantly reduces the quality and integrity of any analysis or report based on such data. This restriction is due to several factors that can affect the findings' reliability and comprehensiveness.

1. Incomplete Understanding of Patterns:

When essential variables like as the country, type of attack, casualties or target information are missing, it is difficult to completely understand the patterns and features of terrorist attacks. The ansence of critical data points can result in skewed conclusions, as the study may not adequately reflect the underlying nature of terrorism patterns.

2. Reduced Sample Size:

Deleting rows and columns with missing data may seem like a tempting approach or sometimes the only solution, but it reduces the overall sample size available for analysis. A limited dataset reduces the statistical strength of any conclusions obtained, making it more difficult to apply findings to the larger population of terrorist attacks. However, in order to produce a high-quality report, all blank rows and columns must be removed.

3. Data Reporting Inconsistencies:

Missing values can cause inconsistencies in reporting by forcing analysts to make assumptions or approximations. This can result in inconsistencies between the reported conclusions and the actual situation, decreasing the analysis's credibility.

### 🔖 References

In order to complete this project, I watched a number of YouTube videos; here are a few that I found quite helpful:

1. Power BI installation:
   - [Watch Tutoril 1 Here](https://youtu.be/TmhQCQr_DCA?si=n9M3BtTqsra8JCBx)
   - [Watch Tutorial 2 Here](https://youtu.be/NNSHu0rkew8?si=jn8xYbfOsovmpeBl)
  
2. Power BI Tutorial for Beginners (2024) by Guy in a Cube:
   - [Watch Tutorial Here](https://youtu.be/udzsJqUZPrY?si=qgCRE0fW47Zl6M7l)


