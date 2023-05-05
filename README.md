Download Link: https://assignmentchef.com/product/solved-ds501-homework-3-collecting-manipulating-and-blending-data-from-twitter
<br>
<h1>Problem 1: Sampling Twitter Data with Streaming API about a certain topic</h1>

<ul>

 <li>Select a topic that you are interested in, for example, “#WPI” or “#DataScience”</li>

 <li>Use Twitter Streaming API to sample a collection of tweets about this topic in real time. (It would be recommended that the number of tweets should be larger than 50, but smaller than 500.</li>

 <li>Store the tweets you downloaded into a local file (csv file)</li>

</ul>

<table width="632">

 <tbody>

  <tr>

   <td width="632"><strong>library</strong>(twitteR) <strong>library</strong>(stringr)<strong>setup_twitter_oauth</strong>(consumerKey, consumerSecret, accessToken, accessTokenSecret) tweets = <strong>searchTwitter</strong>(‘#rstats’, n=50) tweetsDF = <strong>twListToDF</strong>(tweets)</td>

  </tr>

 </tbody>

</table>

Report some statistics about the tweets you collected

<ul>

 <li>The topic of interest: &lt; INSERT YOUR TOPIC HERE&gt;</li>

 <li>The total number of tweets collected: &lt; INSERT THE NUMBER HERE&gt;</li>

</ul>

<h1>Problem 2: Analyzing Tweets and Tweet Entities with Frequency Analysis</h1>

<ol>

 <li><strong>Word Count:</strong>

  <ul>

   <li>Use the tweets you collected in Problem 1, and compute the frequencies of the words being used in these tweets.</li>

  </ul></li>

</ol>

<em># Your R code here</em>

<ul>

 <li>Display a table of the top 30 words (ONLY) with their counts</li>

</ul>

<em># Your R code here</em>

<ol start="2">

 <li><strong>Find the most popular tweets in your collection of tweets</strong>

  <ul>

   <li>Please display a table of the top 10 tweets (ONLY) that are the most popular among your collection,</li>

  </ul></li>

</ol>

i.e., the tweets with the largest number of retweet counts.

<em># Your R code here</em>

<ol start="3">

 <li><strong>Find the most popular Tweet Entities in your collection of tweets</strong></li>

</ol>

1

Please display a table of the top 10 hashtags (ONLY), top 10 user mentions (ONLY) that are the most popular in your collection of tweets.

<em># Your R code here</em>

<h1>Problem 3: Getting any 20 friends and any 20 followers of a popular user in twitter</h1>

<ul>

 <li>Choose a twitter user who has many followers, such as @hadleywickham.</li>

 <li>Get the list of friends and followers of the twitter user.</li>

 <li>Display 20 out of the followers, Display their ID numbers and screen names in a table.</li>

 <li>Display 20 out of the friends (if the user has more than 20 friends), Display their ID numbers and screen names in a table.</li>

 <li>Compute the mutual friends within the two groups, i.e., the users who are in both friend list and follower list, Display their ID numbers and screen names in a table</li>

</ul>

<strong>Problem 4 (Optional): Explore the data</strong>

Run some additional experiments with your data to gain familiarity with the twitter data and twitter API