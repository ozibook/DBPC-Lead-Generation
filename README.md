# DBPC-Lead-Generation
Lead Generation repository for Twitter and LinkedIn.

## Task Description 📜
Understanding and engaging with our target audience is vital for addressing their specific needs and catering to our niche market. The creation of a Target Audience Database, sourced from Twitter, serves as a foundational step in our strategy to drive business growth. This task description outlines the process of scraping and building a comprehensive database of potential cold leads from Twitter, with the ultimate goal of converting them into warm leads through personalized content.

[Go to the notion page for detail understanding of the task↗️](https://docs.google.com/document/d/1lpqrSfYIm4M5RGakFS-gzObmP9jVybTxDKrgsuAAelc/edit#heading=h.kxzno2lukev)

## Task Objective 🎯
The primary objective of this task is to establish a Target Audience List consisting of potential clients and cold leads. These profiles will serve as the foundation for our efforts to engage with them and eventually convert them into warm leads through personalized content.

### 📁 File Details
1. Twitter_Profile_Scrapper_RohitPani
- Code file for scraping twitter profiles
- [Go to File↗️](https://github.com/ozibook/DBPC-Lead-Generation/blob/main/Twitter_Profile_Scrapper_RohitPani.ipynb)
<details>
<summary>Code Explanation</summary>
<br>
-How to use </br>
Setup:
--> Ensure you have Python installed.

--> Install the required libraries using pip (selenium, pandas, webdriver_manager, etc.).

Run the Script:</br>
--> Execute the provided script in your terminal or IDE.

Input Usernames:</br>
--> When prompted, enter the number of Twitter profiles you wish to scrape.

--> Provide the usernames for the entered number of profiles.

Login to Twitter:</br>
--> A browser window (Chrome) will open, taking you to the Twitter login page.

--> Manually log in to your Twitter account within the allotted 25 seconds.

Wait:</br>
--> The script will automatically visit each profile, scrape the desired information, and store it in memory.

Check the Output:</br>
--> Once the script completes, find two Excel files in the script's directory: twitter_data.xlsx (contains profile information) and twitter_hashtags.xlsx (contains hashtags from the tweets).

Done!:</br>
--> Review the scraped data in the Excel file.

--> If any data is not present, it will leave a blank space in that column.


- To install the packages silently
 
![image](https://github.com/ozibook/Target_Audience_Analysis/assets/144370840/96fabda5-91cc-4177-8e64-93380a49cf1a)

 - To add the Excel file
![image](https://github.com/ozibook/Target_Audience_Analysis/assets/144370840/0d1325d6-ac22-4a0a-9d99-ae0a7d422822)

 - Remove Duplicates
![image](https://github.com/ozibook/Target_Audience_Analysis/assets/144370840/36bd39e5-e8bf-4b93-b2f6-023bba952be9)


</details>
 

2. Linkedin_Profile_Scrapper_Ozigen_Updated_dbpc.ipynb
- Code file for scraping linkedin profile data and related metrices.
- [Go to File↗️](https://github.com/ozibook/DBPC-Lead-Generation/blob/main/Linkedin_Profile_Scrapper_Ozigen_Updated_dbpc.ipynb)

 
# Installation Guide👨‍💻
The following libraries are required to run the code<br>
1. Install Requests<br>
```
!pip install requests --quiet
```
2. Install Selenium <br>
```
!pip install selenium --quiet
```
3. Install Web driver<br>
```
!pip install webdriver_manager --quiet
```
4. Install Pandas<br>
```
!pip install pandas --quiet
```

# FAQs❓
 * Which environment to choose?
   - It is recommended to use Jupyter Notebook.

# Author & Contributions
- Rohit Pani

