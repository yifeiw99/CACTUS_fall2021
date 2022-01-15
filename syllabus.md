

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
			* https://www.youtube.com/watch?v=AuTkAWEa06E&ab_channel=HongLy
		or
			* https://test-jupyter.readthedocs.io/en/latest/install.html


	**2.	Set up Twitter data collection requirements**

		* Read: 

			* https://towardsdatascience.com/getting-started-with-data-collection-using-twitter-api-v2-in-less-than-an-hour-600fbd5b5558

			* https://medium.com/geekculture/how-to-get-twitter-data-with-tweepy-4663fbc8b90b

		* Explore the process to apply for a Twitter developer key following the reading linked in 2.a.ii. If you don’t have a Twitter developer account yet, write up an imaginary research project like this: https://www.dropbox.com/s/2b735yqa1h6utbt/Twitter_example_application.pdf?dl=0

		* If you are clear on your research project already, then you can apply for a Twitter Developer account. Be as detailed as possible in describing your research project, and clarify your university and who is your mentor. Link their Google Scholar profile: https://developer.twitter.com/en/apply-for-access

		* If you are not clear, then just start drafting out your application and we will talk about it in class


	**3.	In class**

		* We will go over your problems

		* We will simply explore: (note that this is restricted use for only the students enrolled in this tutorial. Please do not share further or use without permission)
		Isentia Workbench: https://workbench.brandtology.com/



### Week 1 - APIs
Create separate Jupyter notebooks for each of Step 1,2, and 3. We are just getting warmed up at the moment to understand and explore the different kinds of APIs. 
Please create a GitHub account.

	**Read**
	
	Mukerjee, S., & Gonzl̀ez-Bailn̤, S. (2020). Social Media Data: Quantitative Analysis. SAGE Publications Limited. Available in the resources folder.


	**1. Set up YouTube data collection requirements**

		* Read: https://towardsdatascience.com/an-easy-python-wrapper-for-youtube-data-api-3-0-a0f1b9f4c964 to get started with YouTube data collection

		* Get a YouTube API key

		* Install the YouTube python package

	**2. Set up Reddit data collection requirements**

		* Read and install the packages mentioned in https://medium.com/mcd-unison/using-pushshift-api-for-data-analysis-on-reddit-b08d339c48b8

	**3. Create your own documentation (DUE WEEK 3)**

		* Choose the data source you want to work with, e.g., TikTok, Weibo

		* Create a list of resources for this data source (links to how to apply for an API key, which python packages to use, existing code repositorities) 

		* If one already exists, use it but build on it.

	**4. Start brainstorming on ideas for the research problem and the data source which you want to explore in your final project**




### Week 2 - APIs continued + Decide upon a tractable research question that involves analysis of textual data

	**Read**

	Nguyen, D., Liakata, M., DeDeo, S., Eisenstein, J., Mimno, D., Tromble, R., & Winters, J. (2020). How we do things with words: Analyzing text as social and cultural data. Frontiers in Artificial Intelligence, 3, 62. Available in the resources folder.


	**1. Corpus compilation**
	
		* Explore the Twitter and Facebook notebooks

		* Using APIs to compile a corpus (e.g. Tweets by a set of users, All Facebook posts by a news outlet)

		* Explore the part of code in the notebooks that converts JSON to CSV. Can you try to add more fields to be written into the csv in to the "append_to_csv" command?


	**2. Set up newspapers APIs and think about what data you want to collect**

		* Read and follow the steps at: https://towardsdatascience.com/scraping-news-and-articles-from-public-apis-with-python-be84521d85b9

		* As in the above article, sign up to get an API at https://developer.nytimes.com/

		* Sign up to get an API key with https://newsapi.org/

		* Sign up to get an API key with https://mediacloud.org/

		* Try out all the notebooks: N1, N2, MC00a, MC00b, MC01

	**3. Plan your research design before collecting your data (DUE on DEC 4)**

		* Answer the following questions, which you will address in your next week as you collect data (taken from this week's reading!): 

		* Research questions: 

			* What are your research questions and hypotheses? Is this an interesting problem to study? Why?

			* Why is computational text analysis necessary or valuable for answering the research questions?

		* Data:

			* What kind of data do you need to answer these questions? For what time period? From how many sources? How will you get it?

			* Are sources representative? Are they disproportionately of one form? Are all relevant time windows covered? Does the data represent all relevant groups, including those often marginalized?

			* If you are filtering, subsampling, or selecting from the original data, is the remaining subset representative? Can you describe how selective removal alters the data and the interpretation of the data? Are you losing anything that might be valuable at a later stage?

		* Operationalization:

			* Which units of text are most suited to capturing the concepts?

			* Which textual pre-processing steps are appropriate for your task and data? What information gets lost with each preprocessing step, and what is gained? What errors maybe introduced? 

			* Which text analysis steps might be appropriate to answer your question? 


	** (OPTIONAL) First-time Python user? Start here**

		* Watch the video (30 minutes): https://www.youtube.com/watch?v=Z1Yd7upQsXY&ab_channel=CSDojo

		* Bookmark this, do one chapter a week: https://python.swaroopch.com/




### Week 3 - Data collection and Identify, retrieve and prepare a relevant corpus

	**Read**

	Hovy, D. (2020). Text Analysis in Python for Social Scientists: Discovery and Exploration. Cambridge University Press. Chapter 2


	**1. Explore the visualization: http://www.data-nomadic.com/03-01-19 (Thanks Jacob Parelman!) 

	**2. Explore the data behind the visualization (see this week's notebook, 01.exploring_the_oscars_speeches_corpus.ipynb)

	**3. Together with the chapter use, the notebook to understand words, phrases and tokens**

	**4. Try out the notebooks with your own data**

	**5. Complete the Step 3 under Week 2 (Plan your research design before collecting your data) and report in class**


### Week 4 - Progress report and other interesting content: entities, hashtags, mentions, and URLs

	**Read**

	Walter, D., Ophir, Y., & Jamieson, K. H. (2020). Russian Twitter accounts and the partisan polarization of vaccine discourse, 2015–2017. American Journal of Public Health, 110(5), 718-724.

	Walter, D., & Ophir, Y. (2019). The Elephant and the Bird: Republican Candidates' Use of Strategy and Issue Framing in Twitter During the 2016 Republican Presidential Primaries. International Journal of Communication (19328036), 13.

	Salganik, M. J. (2019). Bit by bit: Social research in the digital age. Princeton University Press. Chapter 2.

	Di Caro, L., & Grella, M. (2013). Sentiment analysis via dependency parsing. Computer Standards & Interfaces, 35(5), 442-453.

	Pang, Y., Jia, Y., Li, A., Song, D., & He, R. (2016). Influence of dependency parsing on the prosody of Chinese discourse. In Proceedings of speech prosody.


	**1. Explore the notebooks for this week

	**2. Identify what kind of information you want to collect to fulfill your research objectives

	**3. What do you need to do to get it?**

	**4. Report on progress next week**


### Week 6 - Discussion and presentation planning
	
	You will discuss with each other, plan and get feedback what you will present about your data. It doesn't need to be your final research question, just an intermittent step that is currently possible with what you have learnt.

	Keep in mind: the prompts of Week 2.
	
	Consider what analysis you want to do to answer your research question (entities? Sentiment? Phrases? Word cloud?) 

	What are the challenges you expect to face? How will you try to solve them? Can you help each other?

	In a 7 minute presentation next time, present the Research Problem, Research Question, Data, and Insights that answer or come close to answering the question. 


### Week 7 - Presentations and Sentiment analysis (26th Dec)



### Week 8 - Topic analysis

From the Towards Data Science blog: LDA is a generative probabilistic model that assumes each topic is a mixture over an underlying set of words, and each document is a mixture of over a set of topic probabilities.

We can describe the generative process of LDA as, given the M number of documents, N number of words, and prior K number of topics, the model trains to output:

psi, the distribution of words for each topic K

phi, the distribution of topics for each document i


Parameters of LDA

Alpha parameter is Dirichlet prior concentration parameter that represents document-topic density — with a higher alpha, documents are assumed to be made up of more topics and result in more specific topic distribution per document.

Beta parameter is the same prior concentration parameter that represents topic-word density — with high beta, topics are assumed to made of up most of the words and result in a more specific word distribution per topic.


	**Read**

	Hovy, D. (2020). Text Analysis in Python for Social Scientists: Discovery and Exploration. Cambridge University Press. Chapter 9

	Atkins, D. C., Rubin, T. N., Steyvers, M., Doeden, M. A., Baucom, B. R., & Christensen, A. (2012). Topic models: A novel method for modeling couple and family text data. Journal of family psychology, 26(5), 816.

	Just read: LDA on the Texts of Harry Potter. https://towardsdatascience.com/basic-nlp-on-the-texts-of-harry-potter-topic-modeling-with-latent-dirichlet-allocation-f3c00f77b0f5.

	Just read first: https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/


	** 1. There are two main methods of topic modeling in these resources. Step 1 to 11 remain the same in all cases.

	** 2. Run the notebook till step 11. Pay attention to step 11. What is stored in id2word, texts, and corpus? Can you understand what corpus is representing? Try to run it with the data given, or you can try the descriptions of column of the wine file.

	** wine = pd.read_csv("archive/winemag-data_first150k.csv")

	** 4. Now run step 11 to 15. 

	** 5. The second method is using MALLET. Now try Step 16 onwards.

	** 6. Run the notebook on your data. Where do you get stuck? Try to make it all the way to Step 21.

### Week 9 - Topic distributions, visualization, and MALLET

	Continued from last week:

	1. Model tweaking:
		
		a. Learn to save your model and files after POS-tagging so that you don't need to rerun:
			import json
			with open(‘your_file.txt’, ‘w’) as f:
    		for item in data_lemmatized:
        		f.write(“%s\n” % item)

        	Then when you reopen your notebook, you can read the file into a variable and you are good to go.

		b. Filter out the verbs and see whether it helps with quality

		c. Change the number of topics and see whether it helps with quality. Note the perplexity and coherence with different settings.

	2. Code for the topic distribution per social media post: https://github.com/storopoli/topic-modelling/blob/master/Notebooks/gensim-topic-modeling-visualization.ipynb
	
		The relevant code starts at "What is the Dominant topic and its percentage contribution in each document". You can copy the code into new cells into your existing notebook. First from the menu bar click "insert"->"insert cell below" and then paste the new code into a new cell

	3. I will add code to run MALLET directly (without the gensim wrapper) and share it with you all.

	4. Resources for Chinese topic modeling: Read the paper below and explore : https://www.dropbox.com/sh/r6puasgfq1betli/AACOojkG_d_yxG-XaI5Lqs2Wa?dl=0 (I will add this to GitHub later)

	5. Other visualizations: 

		a. Bar plots: See ideas at https://kokiljaidka.files.wordpress.com/2021/03/crowdtangle-shaheenbagh.pdf for labeling bar plots with example posts. How to find example posts? See the notebook above from storopoli. 
	
		b. Word clouds: https://github.com/amueller/word_cloud/tree/master/examples

	READ
	
	**Park, G., Yaden, D. B., Schwartz, H. A., Kern, M. L., Eichstaedt, J. C., Kosinski, M., ... & Seligman, M. E. (2016). Women are warmer but no less assertive than men: Gender and language on Facebook. PloS one, 11(5), e0155885.

	**Cui, J., Zhang, T., Pang, D., Jaidka, K., Sherman, G., Jakhetiya, V., ... & Guntuku, S. C. (2021). Social Media Reveals Urban-Rural Differences in Stress across China. arXiv preprint arXiv:2110.15726. Available at https://arxiv.org/abs/2110.15726
	


### Week 10 - Sentiment analysis and Time series


	**Read**

	Bucy, E. P., Foley, J. M., Lukito, J., Doroshenko, L., Shah, D. V., Pevehouse, J. C., & Wells, C. (2020). Performing populism: Trump’s transgressive debate style and the dynamics of Twitter response. New Media & Society, 22(4), 634-658.

	Khosla, S., Chhaya, N., Jindal, S., Saha, O., & Srivastava, M. (2019, November). Do events change opinions on social media? Studying the 2016 US Presidential debates. In International Conference on Social Informatics (pp. 287-297). Springer, Cham.


### Week 11 - Time series analysis: Interrupted time series


### Week 12 - Writing up the method and interpreting the findings


### Week 13 - Advanced topics: Social network analysis, machine learning





