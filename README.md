ConcertTweets
=============

## A Multi-Dimensional Data Set for Recommender Systems Research


In an effort to facilitate scientific research purposes and further enable collaborations among researchers in the data mining, machine learning, and computer science communities, we publicly release the 'ConcertTweets' data set. 

'ConcertTweets' combines implicit and explicit user ratings with rich content as well as spatio-temporal contextual dimensions and social network data. The data set can be easily further enriched with additional dimensions and ratings. "<a href="http://pages.stern.nyu.edu/~padamopo/data/ConcertTweets.pdf" target="_blank">ConcertTweets: A Multi-Dimensional Data Set for Recommender Systems Research</a>" provides a detailed description of the data set. 

The latest version of this data set contains 250,000 ratings from 61,803 users referring to 116,344 musical shows and concerts of 23,865 artists and bands. In particular, the data set consists of the following files:
  - **users.dat** Contains the information of the users. The user IDs correspond to the Twitter API user ID. The following information is included: user ID. Additional information can be retrieved using the Twitter API and the provided IDs. 
  In order to obtain additional information, such as the corresponding social network and the description of the user profile as well as the number of followers, friends, and tweets of each account, corresponding to the time of each collected rating, you are encouraged to contact the authors.
  
  - **events.dat** Contains the information of the musical concert. The following information is included: event ID, event date, city, state (or country), latitude, longitude, venue, and event URL.
  
  - **ratings.dat** Contains the concert rating information. Ratings are either explicit, expressed on a scale of 5 (higher values denoting higher appreciation), or implicit, indicating whether a user will attend an event. The following information is included: user ID, band, rating, event ID, venue, event URL, and timestamp.





Earlier versions can be found here: http://pages.stern.nyu.edu/~padamopo/data/concertTweets/ 

Using the unique (Twitter) user identifiers, this data set can be further enriched with cross-domain (e.g., books, movies) user activity. Datasets to consider for cross-domain research include https://github.com/sidooms/Twitter-ratings and <a href="https://github.com/sidooms/MovieTweetings" target="_blank"> MovieTweetings</a>.
 
<br/>

If you use 'ConcertTweets' in your work, please cite the following paper: 

> Panagiotis Adamopoulos, Alexander Tuzhilin: *Estimating the Value of Multi-Dimensional Data Sets in Context-based Recommender Systems*. ACM Conference on Recommender Systems (RecSys 2014)

		@inproceedings{adamopoulos2014estimating,
		  title={{Estimating the Value of Multi-Dimensional Data Sets in Context-based Recommender Systems}},
		  author={Adamopoulos, Panagiotis and Tuzhilin, Alexander},
		  booktitle={8th ACM Conference on Recommender Systems (RecSys 2014)},
		  location={Foster City, Silicon Valley, USA},
		  year={2014}
		}

