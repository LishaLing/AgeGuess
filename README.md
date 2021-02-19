# AgeGuess
Do Asians really think that white people always look older than they really are?

When I played the game of ageguess.org, I found that I often give an older age to the Caucasian/White people. It made me remind in Asia, people says that the White people often looks like older than their really age. Is it really?

So I used the data of ageguess.org, and try to analysis them.

First, I used python to clean the data, to get the Asian gamers & non-Asian gamers, the photos'owner - Asian & non- Asian & White.
#Related Data: 
#Gamers: uid, points, ethnicity.
#Guess: uid, photo_id, ageG, outG.
#photos: photo_id, age, ethnicity.

I then analysed the correlations of Asian gamers and powner_ethnicity_all(asians_all ), Asian gamers and powner_ethnicity_Asian(asians_asian), Asian gamers and powner_ethnicity_non-Asian(asians_non_asian ), Asian gamers and powner_ethnicity_white(asians_white ),separately.

I got the mean data: 
asians_all          0.3388
asians_non_asian    0.4153
asians_white        0.4485
asians_asian       -0.6237

I have created two-dimensional bar charts and outG scatter diagram for each of them.
I have also drawn a line chart for the overall results.
I have just done a sample analysis of the gamers' guessed samples of the ethnic group.

Based on the code in this article, there are many similar analyses that can be done and I hope you find them useful.
It was an unfinished project due to time constraints, but it was a meaningful project that could be explored in many interesting ways based on the ageguess data.
Here is a reference article. https://www.nature.com/articles/s41597-019-0245-9#Sec12
