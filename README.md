# Amazon_review_scraper
Quick Scraper to get the reviews of a product on amazon website.
## Introduction
This little notebooks shows how quickly we can scrape the reviews and ratings of a particular product on Amazon website using "requests_html" python library.


### Example: 
I have use a random product review page as a URL to show the usability of the function.The steps are :

1.  Get a URL of review page of the product you want to scrape data for.
2.  Start the session. 
3.  Run the scrape function.
4.  Get the output in clean tabular form which has three fields(title,rating and body of the review).
5.  This data can be useful in analysis such as NLP based review prediction.
