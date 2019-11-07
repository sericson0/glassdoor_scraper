This code can be used to scrape company reviews from glassdoor. 
Much of the code was taken or adapted from https://github.com/MatthewChatham/glassdoor-review-scraper
and please give credit to Matthew Chatham for all of his hard work and well written code.

Changes from original Chatham code include
	-fixed broken pointers
	-implemented a couple of speedups to make the code run faster
	-allows for multiple companies to be scraped



-------------Make sure you have selenium and pandas installed------------------

-------------Need a glassdoor username and password----------------------------
it is free to get a username and password from the glassdoor website, which can then be added to the code.

Change Limit to number of reviews you would like to scrape. (Code will currently fail if Limit is set above total number of reviews)

Set company names along with the number (along with the E) for the glassdoor review urls for each company you want to scrape      


  