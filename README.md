# LinkedIn-Profile-Analysis
![logo](https://github.com/saraswathi2000/LinkedIn-Profile-Analysis/blob/main/Saraswathi%20Pandit.png)
## LinkedIn Profile Data Analysis using Power BI
### Steps Involved In the Project :-
#### 1) Data Extraction And Exploration 🔍
* The data used in this project was extracted from LinkedIn itself. 
You Can also extract your profile data from LinkedIn by (LinkedIn - > Settings and Privacy -> Data Privacy -> Get a Copy of your Data)

* After the data was extracted, I loaded it into my PowerBI. I came to know that all the different tables such as connections, social activities, and companies were present and had date columns but needed a common date table to change accordingly.
So, to solve that we go to the next stage which is Data Transformation. 

#### 2) Data Transformation ⚒️
* It was seen that some of the tables such as “companies” had different date formats than that of “connections”. So, the 1st step of the data transformation I did was to convert all the dates columns of all the tables into one format (DD-MM-YYYY).
* Next step was to create a Custom Calendar Table using Power Query. The new calendar table contains a date column with all the dates in (DD-MM-YYYY).

#### 3) Building Relation Between the Tables 🤝
 * After the creation of the Custom Calendar table the Date column of Custom Calendar was Joined with the Date column of other tables.
 * That is all the tables were now related to the Custom Calendar table. So that we can apply filters to the data concerning the date.

#### 4) Final Dashboard 📊
 *  Finally started building the Dashboard.
 *  The Dashboard contains 3 pages: -
 1. Home 
 2. Profile Analysis
 3. Connections Analysis
 

#### 5) Publishing the Dashboard 📰
 * This is the last stage where I published my Dashboard from the PowerBI desktop to the PowerBI cloud. 
 * So, in the future, if any changes are made in my local PowerBI file would reflect directly there.
 
### Checkout and Interact with my Dashboard On: - 


## Insights
* Total Number Of Connections across the years 2020,2021 and 2022 is 118
* Highest Number of connections happend in the year 2020 i.e 43
* 13.33% of my Connections are Working as a Data Analyst
* Total Number of Connection Invitations is 82
* Highest Number of connections invitations were seen in 2022 Quarter 3 i.e 38
* Total Course Certifications Achieved is 3
* Total Number of companies followed by me is 12
* Number of posts till December 2022 is 5
* Total Number of Messages(sent and received) is 186
* Total Number of Messages sent is 53(28.49% of total)
* Total Number of Messages Received is 133(71.51% of total)

