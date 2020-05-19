# Capstone-Project--Amazon-review-text-classification-based-on-customer-rating-using-NLP

Amazon is one of the largest online vendors in the World. People often gaze over the products and reviews of the product before buying the product on amazon itself. Amazon customer reviews of products and their review system is accessible across all channels presenting reviews in an easy-to-use format. The product reviewer submits a rating on a scale of 1 to 5 and provides own viewpoint according to the whole experience. 
Though product ratings on Amazon are aggregated from all the reviews by every customer, each individual rating is actually only an integer that ranges from one star to five stars. This reduces our predictions to discrete classes totaling five possibilities. Therefore, what we'll have is a supervised, multi-class classifier with the actual review text as the core predictor.
This project is an exploration of Natural Language Processing (NLP). The goal of predicting the star rating given a piece of text will take on different NLP topics including word embedding, topic modeling, and dimension reduction. From there, a final data frame will be achieved and by employing different machine learning techniques to it in order to come up with the best approach for our classifier  that would understand the essence of a piece of review and assign it the most appropriate rating based on the meaning of the text. Use machine learning techniques to design the classifier and also design a system that pre rates new reviews on their helpfulness before they are given a position at top in the search. Also, the new system that is built will use set of the present data to predict the usefulness classification for new input data.


Introduction:
Amazon is one of the largest online vendors in the World. People often gaze over the products and reviews of the product before buying the product on amazon itself. Amazon customer reviews of products and their review system is accessible across all channels presenting reviews in an easy-to-use format. The product reviewer submits a rating on a scale of 1 to 5 and provides own viewpoint according to the whole experience. 
Though product ratings on Amazon are aggregated from all the reviews by every customer, each individual rating is actually only an integer that ranges from one star to five stars. This reduces our predictions to discrete classes totaling five possibilities. Therefore, what we'll have is a supervised, multi-class classifier with the actual review text as the core predictor.

Problem Statement:
The problem being addressed in this project is the poor quality of Amazon reviews
•	Amazon’s system, in particular, then allows for the higher rated comments to be displayed at the top of the review forum so that new users can see the top-rated comments in order to help them make their own purchasing decisions.
•	The Reviews provide objective feedback to a product and are therefore it is mainly useful for consumers. These ratings are often summarized by a numerical rating, or the number of stars. Whereas, there is more value in the actual text itself than the quantified stars. And at times, the given rating does not truly convey the experience of the product, the gist of the feedback is actually in the text itself. 

Solution:
•	The goal therefore is to build a classifier that would understand the essence of a piece of review and assign it the most appropriate rating based on the meaning of the text.
•	Use machine learning techniques to design the classifier and also design a system that pre rates new reviews on their helpfulness before they are given a position at top in the search.
•	The new system that is built will use set of the present data to predict the usefulness classification for new input data.

Dataset Description: 
Customer reviews on Books dataset is used.
The dataset is downloaded from the link: http://jmcauley.ucsd.edu/data/amazon/
The Amazon books review dataset contains the customer reviews of all listed Books spanning from May 1996 up to July 2014. 
The dataset has 889801 rows and 9 columns
