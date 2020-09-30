# An Analysis of the members in (Sandy) Alex G 666posting
The analysis without code chunks is [here](https://htmlpreview.github.io/?https://github.com/tnieuwe/Alex_G_666posting/blob/master/666posting_analysis_no_code.html), and the analysis with code chuncks is [here](https://htmlpreview.github.io/?https://github.com/tnieuwe/Alex_G_666posting/blob/master/666posting_analysis_w_code.html).

## What is this?
An analysis of survey results from a Facebook Group known as (Sandy) Alex G 666posting that I completed in R.

## Who is Alex G
 Alex G is a somewhat prominent indie musician out of Philly.  He has been writing music for 10+ years and is, at the time I'm writing this, is 27. I'm not going to give his entire history, but when people think of "succesful bedroom artists" (a moniker he doesn't like), he is one of the artists people think of. Up until the release of Beach Music all of his albums were recorded and mixed by him. He is also a multi-instrumentalist, playing almost all fo this instruments on his recordings. His songwriting, lyrics, and production all come together to create an engaging experience I always find myself coming back to. To paraphrase him in an interview "I want my music to hit the 7th time you've listened to it". In my opinion he is one of the greatest and most prolific musicians working today with (including unreleased music) a 200+ song discography. I understand that he's not everyone's cup of tea, but man is he mine. 
 
 ## What is a 666posting?
It is a Facebook group for people who are a fan of Alex G where we discuss his music and share memes. The idea behind the group is explained well by this [article](https://www.vice.com/en_us/article/4agvdm/facebook-shitposting-groups-are-the-new-fan-clubs-for-indie-bands), or at least explains the phenomenon that these types of groups are a part of. In the analysis you'll see the full story, but I made a graph for the group, got approval to make a survey for the group, and then generated the analysis for the group. It should be noted that I had slowly released this data to the group as I generated it, and that this is the final release collated in an Rmarkdown html. I appreciate every single individual who participated in the survey.

## Data Structure:
+ *code_book.xlsx*: A simple code book explaining the different variables in the main dataset. This includes the original questions that were asked, what they were nenamed to in the R analysis and basic facts about how the questions were answered.
+ *666posting_analysis.rmd*: The markdown file used to generate the main analysis html.
+ *alex_g_analysis.rmd*: The markdown file I used in the original analysis that spawned this project.
+ *Sandy_Survey*:
   + *app.R*: The Shiny App that I will eventually make for individuals to explore the data on their own.
+ *inputs*:
   + *alex_g_final_release.csv*: The final release of the Alex G data, used in the main analysis.
   + *country_code.csv*: A csv file with information of the various countries primarily used to determine the population of each country.
   + *state_census.csv*: A csv file with modern population estimates of each state.
   + *state_long*: A csv file with data on the longitudinal and latitudnal center of a state. 
+ *outputs*:
   + *many files*: I'm not going to go through each one as they're not individually important, but many, not all, of the graphics generated from the analysis are output here. 
