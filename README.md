# Webscraping Github topics !!

## This is my first basic webscraping project in which I used the Request and Beautiful Soup library to scrape Github!! 

### Project Outline:
- We're going to scrape https://github.com/topics
- We'll get a list of topics. For each topic, we'll get topic title, topic page URL and topic description
- For each topic, we will get the top 25 repositories in the topic from the topic page
- For each repo, we'll grab the repo name, username, stars and repo URL
- For each topic we'll create a CSV file in the following format:
```
    Repo Name,Username,Stars,Repo URL
    three.js,mrdoob,69700,https://github.com/mrdoob/three.js

```  
