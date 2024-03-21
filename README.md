# Data Analytics Bootcamp Project One
(Introduction taken from Resources/investigation_aims.docx)

Investigating the trope of “Oscar Bait”

“Oscar Bait” is a well-known term in the movie and movie journalism industry, describing the perceived phenomenon of better movies being released shortly before the Academy Awards nominations voting window opens in January each year.
We are looking to investigate:
-	Are movies released within two months of the Academy Awards Nominations window more likely to be nominated for an award?
(Histogram – release month against no. of nominations/wins)
(Line plot – two lines, year against no. of nominations, line 1 for October – December, line 2 for January – September)
-	Do movie review scores accurately reflect how a movie will perform at the Academy Awards?
(Box plot of a sample of movie review scores through the year, Oscar nominees will be added on in a different colour.)
-	Do movies released within two months of the Academy Awards Nominations window receive higher review scores than movies released outside of that window?
(Scatter Plot – release date against review score)
(Pie Chart – Nominees released within two months of awards vs other nominees)
Together, these questions would illustrate whether “Oscar Bait” actually exists, and whether movie reviews align with Academy Awards results. If we find that movies released later in the year have greater review scores but do not win awards as frequently, this may suggest that the idea of “Oscar Bait” influences journalists when reviewing movies throughout the year.

We will utilise themoviedb.org  API to collect review scores and release dates, and cross reference with the database of winners and nominees found on AminFadaee/Academy-Awards-Data: Data for Academy Awards (github.com).

Team members:  
Athul Madhusudhanan  
Daniel Daniel  
Essa Bostan  
Mujahid Iqbal  
James Hanson

(Analysis taken from Powerpoint Handout - Analysis)

●	Multi Line Plot
•	Across all years tested, more nominated movies are released during “Oscar season”.
•	This is most likely due to the fact that these films are fresher in the mind of the Academy voters. 
•	Limited and strategic releases may also be a factor; some films are shown exclusively to the academy before being opened up to a limited release right before Oscar Season.
•	Does streaming have an impact?
o	With the advent of streaming services like Netflix, Amazon Prime, Disney Plus etc., is there an impact on the number of people going out to see movies at the box office?
o	There has also been an increase of films released direct to streaming, completely bypassing the movie-going audience.


We can see from the pie chart, that in 2013, 30.3% of the Oscar Nominated movies released in November and December. compared to 63.3% of movies released in the rest of the month. These 2 months only take up 16.7% of the year yet contain a lot of nominated films. This means that generally, films released in November or December are significantly more likely to be nominated.

By analysing all three histograms, the common factor shown in these pictures is number of nominations is at the highest for the months of November and December of the chosen years, which means that November and December have the most releases which they showcase and campaign to get a nomination for the Oscars. Another thing which I can relate to with Oscar season and these histograms is: Even though Nov and Dec have the most movies released and showcased, October is the start of the season. In these histograms, you could see October at a number of 2 or 3 nominations followed by a humongous increase of nominations in November or December, which translates to “The Oscar season begins in October with the first batch of releases, which are in small number, followed by a greater number of releases in November and December.” The movies which should be deemed as “Oscar-worthy” are mostly released from October to December to boost or capitalized this season, such that it remains fresh for critics and Academy Awards jury to earn a nomination. Comparing to these histograms, there used to be releases in June to August in 2008, while decreasing to half in 2013, and zero in 2018, which shows the these months are the “dump months”, which means the time period of releases which garners lowered expectations of films.

For our Multi-Box Plots, we can see that surprisingly, the review scores for Oscar Nominated movies released in December, shown in blue, are generally lower than those in other months. This could suggest that a lower standard is required for movies released later in the year to be nominated for an Oscar. We can also see from the Red box plots for Non-nominated movies, that there are movies released throughout the year with much higher review scores than those nominated for an award, particularly in the cases of April 2013 and January 2018. This could come down to genre, indicating that studios prefer to release movies of a more serious tone later in the year, which is what we expected to see.

With regards to our hypothesis, these plots appear to disprove our point, suggesting that a higher average review score does not make a movie more likely to be nominated, and goes further to suggest that movies released in December have a lower bar for nomination.

As you can see from the visualisations, although weak, there is a consistent positive correlation between release date and review score. We could attribute this to a variety of factors: Primarily, and something that we have also tested in our other hypotheses, a factor could be that movies released later in the year are better, as studios release their best movies closer to Awards season to have a better chance of winning an award. We should also consider that Journalists may have bias in their reviews though, as they attempt to predict Oscar nominees to improve their reputation as a reviewer.
To improve these plots, we could have removed outliers for a clearer coefficient line, plotted more years to further reinforce our findings regarding the correlation, or used the full population of movies from the selected years to have a complete picture.

It seems clear from the analysis we have done that “Oscar Bait” is a term that both Studios and The Academy take more and more seriously each year. We saw that movies released in November-December are significantly more likely to be nominated for Oscar Awards, a trend that is increasing year on year, but that yearly trends for average movie reviews, whilst indicating that movies released later in the year do receive higher reviews, have not seen a change demonstrating any relation to nominations.

This could suggest that the quality of movies released later in the year is not improving, but the Academy is taking more notice of movies released later in the year and disproportionately nominating them. Our Multi-Box plot displays this clearly, as the box plot for Oscar Nominated movies would tend closer to the average for Non-nominated movies.
Ultimately, this suggests that "Oscar Bait" is not only real, but the Academy themselves are the main force driving it, and studios simply follow the trends to increase their chances of winning.

For a final thought, we look to the future, and what we can and cannot model going forward. What we can’t predict, is how Streaming will impact this landscape. We saw the impact it had in 2008 when it was first starting to enter, and although it appears to have balanced out, it could allow a wider range of films, particularly lower budget ones, to compete at the awards. Secondly, the Academy may recognize this trend and choose to put a stop to it, changing the way they do the awards. Finally, and I have to mention it because of the effect it has had on our data and the way we conducted our research, there could be another unexpected global event around the corner that could change things even more.
What we can predict from our results: Under the current model, we can expect more and more “Oscar Bait” movies to be released in November and December each year, and this may mean studios release their lower rated movies in the summer. Over time, this could develop into two clear “Movie Seasons”, a summer season where light-hearted family blockbusters are released, and a winter season where studios make their award attempts.
