# Homework-1-Bootcamp-Kickstart
## Background

Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success.  Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt too discover some trick for finding success.  I have been tasked with organizing and analyzing a database of 4,000 past projects in order to uncover any hidden trends.


## Findings

  1. Given the provided data, what are three conclusions we can draw about Kickstarter campaign?
  
      1. After analyzing the data,  I found that there are three parent categories that experience a success rate of greater than 50%.  The          categories are:  Music (77.1%), Theater (60.2%), and Film & Video (57.7%).
      ![alt text](https://github.com/reharris2/Homework-1-Bootcamp-Kickstart/blob/master/Capture.PNG)
      
      1. Each of the Parent Categories above have their successful and unsuccessful categories.
      
         1. Most of the subcategories of the Music group are successful with the exception of jazz and faith music which are                         unsuccessful at 100% and 67% failure rates, respectively.
      ![alt text](https://github.com/reharris2/Homework-1-Bootcamp-Kickstart/blob/master/musicSC.PNG)
      
         1.  Plays are the only successful subcategory of the theater parent group with a 65.1% success rate.  Musicals and spaces have              under 50% probability of success.
      ![alt text](https://github.com/reharris2/Homework-1-Bootcamp-Kickstart/blob/master/musicSC.PNG)
      
         1. In the film & video category, it appears to be either sink or swim.  Documentaries, shorts, and television projects were                   successful at a 100% rate. While the other subcategory projects all failed or were cancelled.
      ![alt text](https://github.com/reharris2/Homework-1-Bootcamp-Kickstart/blob/master/film1SC.PNG)
      
       1. Lastly, after analyzing the data, I conclude that projects that launch during mid-spring to early summer have a better chance           of success while those that launch the November and December have a higher probability of failure.  This may be due to                   conflicts in giving during the holiday season.
       ![alt text](https://github.com/reharris2/Homework-1-Bootcamp-Kickstart/blob/master/LaunchDate.PNG)
       
1. What are some limitations of this dataset?
    
      1. The currencies of the goals and the pledges are different; therefore, comparing projects from different countries or                     currencies are not equivalent unless they are placed on equivalent currency basis.
      1. Approximately 693 of the 4,114 projects or 16.8% have goals of $100 or less.  I believe this inflates the number of successful          projects which may make the trends look better than they really are.
      1. Data on fundraising skills of each organization is not collected, so one of the reasons for project success could be a factor            that we are not accounting for.
      
1. What are some other possible tables and/or graphs that we could create?

      1. A table comparing parent category and sub-categories against the goals would be helpful, so we analyze the data excluding all            projects under $100.
      1. Tables by country would be helpful because the currencies would be equivalent then we could see if the same trends apply across          countries.
      1. A column in the data that placed all currencies on USD basis.
      1. Pie charts could have been used instead of bar charts to display the composition of successful parent/sub categories.
      1. Scatter Plot graph along regression analysis could have been used to determine the factor that most correlated with successful          projects.

