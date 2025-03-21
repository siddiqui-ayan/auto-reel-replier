# unemployed bot 9000
This is a fun project I made for an youtube video to automatically reply to all the reels that I receive using AI.
This bot works by basically taking the top 3 comments of an received instagram reel and sending it to an AI and letting it generate an appropriate response

## 🔧 How to Set It Up

### **1. Clone the repository**
- You can do this by either clicking on the Code button on github and clicking "download ZIP"
- Or you can use git CLI and just run `git clone https://github.com/siddiqui-ayan/auto-reel-replier`

### **2. Prerequisites**
- After you have successfully clone the github repo. You will need to setup 2 things
  1) A Gemini AI api key. [You can get it here](https://aistudio.google.com/app/apikey?_gl=1*1mqhee1*_ga*MTM3MTk0NjE3OC4xNzQyMjcxMjYx*_ga_P1DBVKWT6V*MTc0MjU0NTg5NC4yLjAuMTc0MjU0NTg5NC42MC4wLjIxMDkwNzcwNzg.)
  2) An apify key for scraping the instagram comments. [You can get it here.](https://apify.com/apify/instagram-comment-scraper)
- And for an **instagram** reel replier, you will also need an *instagram account*. duh!

### **3. Setting up the project**
- After you have got everything required to run the bot, you will have to make a few changes
- Rename `.env.example` to `.env`
- Put the neccessary tokens/api keys that we accquired in the previous step and put in the .env

## **4. running the bot**
- After you have successfully completed the above following steps
- You can run the bot by typing in `python main.py` in your terminal/command prompt
- If your followed all the *simple instructions* that even a monkey brain can follow you will see a output like this in the terminal
![image](https://github.com/user-attachments/assets/068cb90a-9f82-48b2-a356-e914430e9c98)


### **5. Success**
- Wohoo! You have now successfully setted up unemployed bot 9000
- Now this bot will be your slave in your place and painfully reply to all your friends' unfunny sent reels
