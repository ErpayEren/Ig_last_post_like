# Instagram Last Post Auto Like

This Python project automates the process of logging into Instagram, visiting a specific account, and liking the latest post using **Selenium WebDriver**.

## Overview
The script automatically:
1. Logs into Instagram with your username and password  
2. Opens your profile and navigates to the “Following” list  
3. Selects a target account  
4. Opens that account’s most recent post  
5. Likes the post and closes the browser

It was built as a small automation experiment to practice **Selenium** and web interaction with Python.

## Technologies Used
- Python  
- Selenium  
- WebDriver Manager  
- Time module  

## Files
- **Instagram.py** → main script  
- **flags.py** → contains your Instagram credentials (username and password)

Example structure:
project_folder/
│
├── Instagram.py
├── flags.py
└── requirements.txt


The `flags.py` file should contain:
```python
kullanici_adi = "your_username"
sifre = "your_password"

How to Run
pip install selenium webdriver-manager
python Instagram.py
The browser will open, log into your account, and automatically like the latest post of the selected account.

!!!
Make sure you have Google Chrome installed.

Use this script responsibly; excessive automation may violate Instagram’s terms of service.

Sleep intervals are included to prevent detection as a bot.

You can change the target username in the XPATH line to interact with different accounts.

