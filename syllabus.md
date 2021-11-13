

## Textbooks and resources

* The main readings on corpus linguistics will come from:
	* Baker, P. (2006) _Using Corpora in Discourse Analysis_. London: Continuum

* and on Python programming and NLP concepts from:
	* Bird, S., Klein, E. & Loper, E. _Natural Language Processing with Python - Analyzing Text with the Natural Language Toolkit._ Updated version for Python 3. Available free online at http://www.nltk.org/book/


## Assessment

This tutorial is intended to help students complete a project that uses the techniques and theory covered in class on a research project of their own. While this tutorial is being offered for no credits, there are minimal expectations in place for any participating students:

1. **Complete the assigned readings and participate in class discussion**
	* Readings for each week will be uploaded to GitHub ahead of schedule.
2. **Attend weekly lab sessions and complete the assigned exercises**
   * We will be using Jupyter notebooks to learn Python, which are a web-based interactive programming environment. Assignments will be completed in this and submitted to the instructor. Details of using this system for assignments will be covered in the first lab session.
	* Weekly assignments will be on the day before the lab session. These assignments are intended to help students practice the programming concepts and structures introduced in lab and build confidence. They should not be difficult or take excessive time but they do build from week to week so it is _very_ important to keep up.
3. **Complete a project that uses the techniques and theory covered in class to carry out a text analysis of a specific research question agreed upon with the instructor (50%)**
    * The goal of this project is to create an engaging blog post similar those produced by data journalists after [State of the Union](https://www.washingtonpost.com/news/monkey-cage/wp/2015/01/21/the-state-of-the-union-address-in-a-single-figure/?utm_term=.1a2854849261) addresses or on a topic like ['How men and women talk about love'](https://www.nytimes.com/interactive/2017/11/07/upshot/modern-love-what-we-write-when-we-write-about-love.html) in the NYTimes recently.
    
    * The steps in the project are: 
         1. Decide upon a tractable research question that involves analysis of textual data, e.g.: 
            * _Did Hillary Clinton's language as candidate change between 2008 and 2016?_
            * _What makes and when is Donald Trump happy (as evidenced on Twitter)?_
            * _What characterises the online media's discussion of poverty/immigration/etc.?_
            * _From smoking to vaping - Examining online testimonials of e-cigarette users_ 
            * _Comparing portrayal of women in rap and country music__
         2. Identify, retrieve and prepare a relevant corpus, e.g. 
            * Clinton 2008 and 2016 campaign speeches 
            * Trumps tweets since 2014
            * Online news coverage of poverty/immigration/..
            * User stories from online vaping forum, etc.)
            * Representative samples of song lyrics
         3. Carry out linguistic analysis of corpus, e.g.
            * Construct comparative frequency lists of 2008 and 2016 speeches by Clinton, identify keywords, collocations and examined and interpret concordance listings
            * Apply approrpriate sentiment analysis techniques to Trump tweet corpus, cluster tweets by sentiment and time, examine distinctive words and phrases
            * Collocation analysis of topic related words (e.g. _poverty, poor, low-income_ or _immigration, immigrants, illegals, illegal aliens_)
            * Create n-gram frequency lists and compare collocations and patterns relating to _smoking_ and _vaping_
            * Examine and compare collocates of words for women between two genres
         4. Visualize data
            * Find appropriate ways to communicate the most important and relevant results from step 3. This might be use a frequency list, concordance listings, a scatter plot of words and phrases, etc. 
         5. Interpret findings
            * How does your text analysis answer your research question?
            * Why and how does it matter?
         6. Write up in a blog post 


            These steps will be scheduled throughout the course allowing for the instructor to help you find a manageable problem, acquire the necessary data and be able to carry out the appropriate computational analysis.
            
     * More details of the kinds of projects that would be appropriate and manageable will be discussed during the first few weeks of class.



## Note about learning programming

A central goal of this class is to help students begin to develop programming skills that they can use to approach questions of interest using the growing amounts of textual data available in the era of 'big data'. But like learning any new skill, such as a new language, it takes time and can be frustrating at first. This course does not require students to have any programming background. Realistically it is not possible to become a fully proficient programmer in just one semester. However, the lab sessions and assignments are focused on helping you begin this process and to become comfortable with reading, understanding and modifying Python code examples that you can find on the web etc.



## Course Schedule

* **N.B.** - This is a tentative schedule that is subject to change


### Week 0 - Orientation

**Orientation day prerequisites (Do by Nov 13):**
Before class, please do Step 1 and 2. It should take you about 2-3 hours at the most. If you have any trouble in these steps, we will discuss it in the tutorial

**1.	Install Python, Anaconda, Jupyter Notebook**
Follow one of the options:
•	https://www.youtube.com/watch?v=AuTkAWEa06E&ab_channel=HongLy
or
•	https://test-jupyter.readthedocs.io/en/latest/install.html


**2.	Set up Twitter data collection requirements**

a.	Read: 

i.	https://towardsdatascience.com/getting-started-with-data-collection-using-twitter-api-v2-in-less-than-an-hour-600fbd5b5558

ii.	https://medium.com/geekculture/how-to-get-twitter-data-with-tweepy-4663fbc8b90b

b.	Explore the process to apply for a Twitter developer key following the reading linked in 2.a.ii. If you don’t have a Twitter developer account yet, write up an imaginary research project like this: https://www.dropbox.com/s/2b735yqa1h6utbt/Twitter_example_application.pdf?dl=0

i.	If you are clear on your research project already, then you can apply for a Twitter Developer account. Be as detailed as possible in describing your research project, and clarify your university and who is your mentor. Link their Google Scholar profile: https://developer.twitter.com/en/apply-for-access

ii.	If you are not clear, then just start drafting out your application and we will talk about it in class


**3.	In class**

a.	We will go over your problems

b.	We will simply explore: (note that this is restricted use for only the students enrolled in this tutorial. Please do not share further or use without permission)
Isentia Workbench: https://workbench.brandtology.com/



### Week 1 - APIS
Create separate Jupyter notebooks for each of Step 1,2, and 3. We are just getting warmed up at the moment to understand and explore the different kinds of APIs. 
Please create a GitHub accounts.


**1. Set up YouTube data collection requirements**

a.	Read: https://towardsdatascience.com/how-to-build-your-own-dataset-of-youtube-comments-39a1e57aade 
Follow the steps in the article in Step 1 until Step 7

b.	Get a YouTube API key

c.	Install the YouTube python package

**2. Set up Reddit data collection requirements**

a.	Read and install the packages mentioned in https://medium.com/mcd-unison/using-pushshift-api-for-data-analysis-on-reddit-b08d339c48b8

**3. Set up newspaper API collection requirements**

a.	Read and follow the steps at: https://towardsdatascience.com/scraping-news-and-articles-from-public-apis-with-python-be84521d85b9


**4. Create your own documentation (DUE WEEK 3)**

a. Choose the data source you want to work with, e.g., TikTok, Weibo

b. Create a list of resources for this data source (links to how to apply for an API key, which python packages to use, existing code repositorities) 

c. If one already exists, use it but build on it.

**5. Start brainstorming on ideas for the research problem and the data source which you want to explore in your final project**





### Week 2 - APIs continued

**1. Corpus compilation**
    * Extracting text from structured data
	  * Using APIs to compile a corpus (e.g. Twitter)
	  * Web scraping and crawling
    * **Readings**: _Baker Chs. 3&4_; _NLTK Book Ch. 3_ http://www.nltk.org/book/ch03.html
	

**2. Write code to read json files and write CSV files (DUE WEEK 4)**

a. Use the "Common How Tos" at https://thepythonguru.com/


	
**3. First-time Python user? Start here**

a. Watch the video (30 minutes): https://www.youtube.com/watch?v=Z1Yd7upQsXY&ab_channel=CSDojo

b. Bookmark this, do one chapter a week: https://python.swaroopch.com/