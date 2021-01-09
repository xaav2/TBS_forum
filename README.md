# TBS_forum

content: 
  - missing.txt: list of topics I have no access to.
  - crawl_missing_forums.py: python script that crawls all the topic from missing.txt, process them and store them in a sqlite3 db.
  
python dependencies:
- sys,re,requests,time (built-in i guess)
- sqlite3 (built-in or pip install pysqlite3)
- beatifulsoup (pip install beautifulsoup4)

usage: 
- download both missing.txt and crawl_missing_forums.py
- review the code of craw_missing_forums to make sure that xaav does not attempt sth funny with your comuter ;-)
- log to tbs and retrieve your session ID
- execute python3 crawl_missing_forums.py <your php session id>
- if it says "new topics found", send the missingTopics.db to xaav!
  
Thank you for your help, toghether we will save TBS!
