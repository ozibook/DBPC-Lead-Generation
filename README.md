# DBPC-Lead-Generation
Lead Generation repository for Twitter and LinkedIn.

## Task Description 📜
Understanding and engaging with our target audience is vital for addressing their specific needs and catering to our niche market. The creation of a Target Audience Database, sourced from Twitter, serves as a foundational step in our strategy to drive business growth. This task description outlines the process of scraping and building a comprehensive database of potential cold leads from Twitter, with the ultimate goal of converting them into warm leads through personalized content.

[Go to the notion page for detail understanding of the task↗️](https://docs.google.com/document/d/1lpqrSfYIm4M5RGakFS-gzObmP9jVybTxDKrgsuAAelc/edit#heading=h.kxzno2lukev)

## Task Objective 🎯
The primary objective of this task is to establish a Target Audience List consisting of potential clients and cold leads. These profiles will serve as the foundation for our efforts to engage with them and eventually convert them into warm leads through personalized content.

## File Details 📁 
###**1. Twitter_Profile_Scrapper_RohitPani**
- Code file for scraping twitter profiles
- [Go to File↗️](https://github.com/ozibook/DBPC-Lead-Generation/blob/main/Twitter_Profile_Scrapper_RohitPani.ipynb)
<details>
     <summary>
      Code Explanation👨‍💻
     </summary>
<br>
     
**How to use:** </br>
Setup:
--> Ensure you have Python installed.

--> Install the required libraries using pip (selenium, pandas, webdriver_manager, etc.).

**Run the Script:**</br>
--> Execute the provided script in your terminal or IDE.

**Input Usernames:**</br>
--> When prompted, enter the number of Twitter profiles you wish to scrape.

--> Provide the usernames for the entered number of profiles.

**Login to Twitter:**</br>
--> A browser window (Chrome) will open, taking you to the Twitter login page.

--> Manually log in to your Twitter account within the allotted 25 seconds.

**Wait:**</br>
--> The script will automatically visit each profile, scrape the desired information, and store it in memory.

**Check the Output:**</br>
--> Once the script completes, find two Excel files in the script's directory: twitter_data.xlsx (contains profile information) and twitter_hashtags.xlsx (contains hashtags from the tweets).

**Done!:**</br>
--> Review the scraped data in the Excel file.

--> If any data is not present, it will leave a blank space in that column.


- Importing the necessary Libraries
  
![image](https://github.com/ozibook/DBPC-Lead-Generation/assets/144370840/9520baef-1b89-43d7-80c6-eaa7cc00927c)

- Function to introduce a random delay time and function to scrape a given Twitter profile
![image](https://github.com/ozibook/DBPC-Lead-Generation/assets/144370840/3718c1f4-ebc1-404b-80a8-d76dfff4e3db)

- Wait for the tweets to load on the page
![image](https://github.com/ozibook/DBPC-Lead-Generation/assets/144370840/87fe000c-08c0-4645-9482-66c1bb180b77)

- Extracting the required number of tweets and their hashtags, getting user input and initializing the chrome web driver
![image](https://github.com/ozibook/DBPC-Lead-Generation/assets/144370840/d6af1471-b51b-4bfd-9189-d03499f2e64f)

- Scraping each profile and saving the data to Excel file
  
![image](https://github.com/ozibook/DBPC-Lead-Generation/assets/144370840/0dfc79de-8323-4132-842e-ced01df5df02)


</details>

###**2. Linkedin_Profile_Scrapper_Ozigen_Updated_dbpc.ipynb**
- Code file for scraping linkedin profile data and related metrices.
- [Go to File↗️](https://github.com/ozibook/DBPC-Lead-Generation/blob/main/Linkedin_Profile_Scrapper_Ozigen_Updated_dbpc.ipynb)
  
<details>
<summary>Code Explanation👨‍💻</summary>
<br>
     
**How to use:** </br>
Setup:
--> Ensure you have Python installed.

--> Install the required libraries using pip (BeautifulSoup, pandas, webdriver_manager, etc.).

**Run the Script:**</br>
--> Execute the provided script in your terminal or IDE.

**Input Usernames:**</br>
--> When prompted, enter the username and password for LinkedIn account with which you want to scrape.

**Login to LinkedIn:**</br>
--> A browser window (Chrome) will open, taking you to the LinkedIn login page.

--> Your details are entered into the LinkedIn login page.

**URLs:**</br>
--> Enter the URLs that are to be scraped in a list format.

**Wait:**</br>
--> The script will automatically visit each profile url, scrape the desired information, and store it in memory.

**Check the Output:**</br>
--> Once the script completes, find a Excel file in the script's directory

**Done!:**</br>
--> Review the scraped data in the Excel file.

--> If any data is not present, it will leave a blank space in that column.

- Importing the necessary Libraries

![image](https://github.com/ozibook/DBPC-Lead-Generation/assets/144370840/6c424a24-5d9c-4ffe-aa67-d4d761fdedd3)

- Code to navigate to the browser ,login to the LinkedIn page and enter user credentials
![image](https://github.com/ozibook/DBPC-Lead-Generation/assets/144370840/7ba373b1-5b4d-42eb-9c76-0898a2fcac67)

- Enter the urls to be scrapped 
![image](https://github.com/ozibook/DBPC-Lead-Generation/assets/144370840/bbc2916d-9ec7-4e19-8b25-6c8671a61b29)

- Profile scraping code
  
![image](https://github.com/ozibook/DBPC-Lead-Generation/assets/144370840/6890394d-1e05-49f8-b364-b360aa8b3386)

- Profile scraping code continuation
  
![image](https://github.com/ozibook/DBPC-Lead-Generation/assets/144370840/cf721d12-dc84-4bec-80da-54b27ccd8fd1)

- Profile scraping code continuation
  
![image](https://github.com/ozibook/DBPC-Lead-Generation/assets/144370840/eec6f673-6f91-4656-9123-8faa8db72efe)

- Profile scraping code continuation
  
![image](https://github.com/ozibook/DBPC-Lead-Generation/assets/144370840/4796b94e-36be-48d5-bc63-e34e07267a93)

- Code to see how many links have been completed and saving the scrapped data to a excel file
![image](https://github.com/ozibook/DBPC-Lead-Generation/assets/144370840/eee94911-10a1-48fc-b127-602677ff0b0f)



</details>

 
## Installation Guide👨‍💻
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

