# GoogleAlertsCrawler
A test project to see if we can get article text from the Google Alerts RSS Feed

The script gets information from a Google Alert feed (https://www.google.fr/alerts) 
and output the content of the article in a xlsx file.

## Installation
- Install Python 3: https://www.python.org/downloads/ 
  - During the installation, enable the option "Add to PATH" to make the next steps easier
- Open a command shell in the project root directory (the one with *main.py* inside) and install the project with 
```
pip install -r requirements.txt
```
- Then run the project with
```
python main.py
```

The results are in the **results** folder. The most recent file contains the latest script execution
result.

## How to configure the Google Alert Feed
- Open the file *config.ini*
- Find the line *rss_feed_url* in the *[GoogleAlert]* section
- Replace the link with the one you want
