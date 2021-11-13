# COVID-Clustering
Ascertaining the existence of ceratin 'communities' extant in Twitter-space during the early days of COVID-19 hysteria

## Project Goal:
   #### Investigate relationships among certain words on twitter in hopes of
## Process:
   #### Used the Python 'Twint' library to scrape roughly 100,000 tweets related to 'coronavirus
   #### Filtered the tweets, using Vader sentiment analyzer, in order to remove sentimentally non-neutral tweets
   #### Sought the most intelligibly-distinct Twitter communities based on natural language processing
   #### Removed stop-words, emails, quotes, new lines characters, and convert the set of tweets into a bag of words
   #### Generated an LDA model for interactive visulization of associated terms
   #### Used word-clouds in order to view words most frequently found in tweets containing the words 'Trump', 'Health', 'Economy', 'Employment', 'Hope'

##  Repo Contents
   #### Tweet-Pipeline Notebook

- ### Latent-Dirichlet-Allocation
   
   <br>
    <p align = "center">
      <img src = "/Graphs/LDA.png" width = 700>
    </p>
   <br>
   
- ### WordCloud generated via 'Economy' request
   
   <br>
    <p align = "center">
      <img src = "/Graphs/econ_wordCloud.png" width = 700>
    </p>
   <br>
   
- ### WordCloud generated via 'Trump' twint request
   
   <br>
    <p align = "center">
      <img src = "/Graphs/trump_wordCloud.png" width = 700>
    </p>
   <br>
   
- ### WordCloud generated via 'Boris' request
   
   <br>
    <p align = "center">
      <img src = "/Graphs/boris_wordCloud.png" width = 700>
    </p>
   <br>
