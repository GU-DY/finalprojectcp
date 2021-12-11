This `README.md` file will be used for your mid-point writeup. Please read all instructions in the `instructions/` directory.
# Mid-point Project Write-up

## How my vision has changed since the proposal?

* I added hero photo and change the layout of the website, because it would be better to have the table of contents on the top and left. 

* Instead of analyzing all the data divided by different teams, I decided to analyze it through three aspects: offense, defense, and shot. Therefore, the linkage needs to change. In addition, I will add more visualizations, especially the interactive one.   

## How my visualization goals changed?

* It did not change but I made it more specifically to two questions: 
      * How he changed his game style in different ages, teams, and game types?
      * What are the keys of him to win the game?

## Does your visualization successfully communicate the story you want to tell? (Rationale for my design choices)

* For static plot, I choose line plot, bar plot, and scatter plot. The color I choose is relevant to hero photo and overall web style. Currently, I display the three points and free throw data to reflect his offense performance. For the numeric and nominal data, I prefer to choose the bar plot, such as the steal and block number. I would add more interactive plot later.    

## At least one screenshot to your document that illustrates your current prototype

* You can access it through index.html and about.html to learn more. 

* ![home-graphone](https://github.com/anly503/project-fall-2021-GU-DY/blob/main/homeone.jpg) 

* ![home-graphtwo](https://github.com/anly503/project-fall-2021-GU-DY/blob/main/hometwo.jpg) 

* ![home-graphthree](https://github.com/anly503/project-fall-2021-GU-DY/blob/main/homethree.jpg)

* ![about-graphone](https://github.com/anly503/project-fall-2021-GU-DY/blob/main/aboutone.jpg) 

* ![about-graphtwo](https://github.com/anly503/project-fall-2021-GU-DY/blob/main/abouttwo.jpg) 

## Add a link to the original data sources.

* As I described in the about section, two main data sources are [Basketball Reference](https://www.basketball-reference.com/players/p/paulch01/gamelog/2021) and [NBA Stats Api](https://github.com/swar/nba_api).

## Briefly describe your current data preprocessing pipeline, if there is one.

* For game log, I need to fill the NA values, change the data types, and created a new variable named result difference to record the game difference. In addition, I need to filter the active game only. At the Final version, I will update it in the About section 2.3 Data Wrangling. 
