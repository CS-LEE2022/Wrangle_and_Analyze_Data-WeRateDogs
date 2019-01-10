## Wrangle and Analyze Data-WeRateDogs


[![](https://img.shields.io/badge/linkedin-@Shilin_Li-orange.svg?colorA=abcdef&logo=data:image/jpeg;base64,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)](https://www.linkedin.com/in/shilin-li-40474777/)


### Introduction


The requirement of current project is to wrangle the tweet archive of **Twitter user** __[@dog_rates](https://twitter.com/dog_rates)__ Twitter data, also known as __[WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs)__, to create interesting and trustworthy analyses and visualizations. 


WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "[they're good dogs Brent](https://knowyourmeme.com/memes/theyre-good-dogs-brent)." WeRateDogs has over 4 million followers and has received international media coverage.


![alt text](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd378f_dog-rates-social/dog-rates-social.jpg)


(Image is from Udacity.)


WeRateDogs [downloaded their Twitter archive](https://help.twitter.com/en/managing-your-account/how-to-download-your-twitter-archive) and sent it to Udacity via email exclusively for us to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. 


The Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing and cleaning is required for "Wow!"-worthy analyses and visualizations. In this project, Tweepy is used to query Twitter's API for additional data beyond the data included in the WeRateDogs Twitter archive.


| Table of Contents |
| :--- |
| <a href='#Prerequisites'> Prerequisites </a> 🔍📜 | 
| <a href='#Design'> Design </a>  📐 |
| <a href='#Conclusions'> Conclusions </a>  📌 |
| <a href='#License'> License </a> 🔖 |


<a id='Prerequisites'></a>

### Prerequisites


![](https://img.shields.io/badge/platform-ios-green.svg?colorA=abcdef)


- Python 3.6.3
- Jupyter Notebook
- Anaconda-Navigator


<a id='Design'></a>

### Design


![](https://img.shields.io/badge/language-Python-orange.svg)


- **_1 Data wrangling_**, which consists of:

    - Gathering data
    - Assessing data
    - Cleaning data


- **_2 Storing, analyzing, and visualizing wrangled data_**


- Reporting on 1) the data wrangling efforts and 2) the data analyses and visualizations


**_It is also worth noting:_**


- We only need original ratings (no retweets) that have images. Though there are 5000+ tweets in the dataset, not all are dog ratings and some are retweets.


- Cleaning includes merging individual pieces of data according to the rules of tidy data.


- The fact that the rating numerators are greater than the denominators does not need to be cleaned. This unique rating system is a big part of the popularity of WeRateDogs.


<a id='Conclusions'></a>

### Conclusions

To sum up, a male dog named Atticus received the highest rating_numerator score which is 1776 as well as highest ratings. A male Chihuahua named Stephan received the highest favorite count (122452) as well as highest retweet count (60735), respectively, surprisingly, the same dog of English_setter breed received the least favorite count (80) and least retweet count (13), notwithstanding, we are still in the dark regarding the rest information.
The names associated higher ratings might be depend on its popularity. Male dogs seem more favored on the market. Even pupper takes over 70.1% of all stages, however, highest rating is correlated with doggo. Taking about the prediction odds, the highest accuracy lies in puppo stage. 


<a id='License'></a>

## License 


[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://github.com/Shilin0806/Wrangle_and_Analyze_Data-WeRateDogs/blob/master/LICENSE)
