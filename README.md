# Olympic-Games-Analysis-1976-2016
Analyze and understand trends of Olympic games across countries over the years.

## Inspiration

Olympics being one of the prestigious competitions in the world, I was curious to know which country did the best, how well women did when compared to men and how it affected the total number of medals they won. So, to get a clearer picture, I picked the last tem Olympic games for my analysis.

## Introduction

The modern [Olympic Games](https://www.olympic.org) or Olympics are leading international sporting events featuring summer and winter sports competitions in which thousands of athletes from around the world participate in a variety of competitions. The Olympic Games are considered the world's foremost sports competition with more than 200 nations participating. The Olympic Games are held every four years, with the Summer and Winter Games alternating by occurring every four years but two years apart.

## Objective
To analyze and understand trends of Olympic games across countries over the years. 

## Link to Python Notebook
[Click here](http://nbviewer.jupyter.org/github/nikhilarosekuruvilla/Olympic-Games-Analysis-1976-2016/blob/master/Python%20notebook/Olympics.ipynb)

## Links to Dataset
* [Historical Olympics data](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results):
This dataset contains Olympics data from Athens 1896 to Rio 2016 of both Winter and Summer Olympics. For the sake of analysis I am only considering Olympic games from the year 1976 i.e last ten Olympics games.
* [Country name data](https://github.com/nikhilarosekuruvilla/Olympic-Games-Analysis-1976-2016/blob/master/country_NOC.csv):
This dataset was used to get full country name from its NOC.

## Tech-stack

* Matplotlib
* Plotly
* Seaborn
* Python(pandas,numpy)

## Insights
> ### 1st Visualization: Top countries with Olympic medals

![figure1](https://github.com/nikhilarosekuruvilla/Olympic-Games-Analysis-1976-2016/blob/master/Visualizations/Medals%20won%20per%20Country%20in%20Summer%20Olympics.png)
![figure1](https://github.com/nikhilarosekuruvilla/Olympic-Games-Analysis-1976-2016/blob/master/Visualizations/Medals%20won%20per%20Country%20in%20Winter%20Olympics.png)

> ### 1st Visualization-II: Gold, Silver and Bronze medals for top 10 countries

![figure1](https://github.com/nikhilarosekuruvilla/Olympic-Games-Analysis-1976-2016/blob/master/Visualizations/Top%20Countries%20in%20Summer%20Olympics.png)
![figure1](https://github.com/nikhilarosekuruvilla/Olympic-Games-Analysis-1976-2016/blob/master/Visualizations/Top%20Countries%20in%20Winter%20Olympics.png)
1. The countries winnning highest number of medals in Summer games are different from those winning in Winter games except USA, Russia and Germany. 
2. We can notice that the top countries at the Olympic games are some of the most developed countries in the world.   
    * Hence, they can provide their atheletes with top-notch facilities, coaches and training centers to excel at their game.
3. At the Winter games we can see that there are very less countries participating compared to Summer games.     
    * This is probably because, for them it's less expensive and they have better infrastructure compared to tropical countries to  train their atheletes for Winter Olympics events.    
    * Most of the countries winning in Winter games are those countries away from the equator or those with colder climates than rest of the world.    
    
> ### 2nd Visualization: Conversion rate to medals

![figure2](https://github.com/nikhilarosekuruvilla/Olympic-Games-Analysis-1976-2016/blob/master/Visualizations/Medal%20to%20Participant%20ratio%20of%20Countries.png)
1. We can see that the three countries with most number of medals(U.S, Russia, Germany) have the highest participant to medal conversion ratio as well. But, what's interesting to note is that Ethiopia, Kenya, Cuba, Jamaica and Netherlands have high conversion ratio but are not present in the top 10 coutries with the highest number of medals.
    * This could be because they are specialised in certain sports where they have very talented athletes along with considerable advantage on their genetic side as well. 
    * For example, if we take Ethiopia or Kenya, athletics, especially long distance running(5000, 10000, marathons), is their forte. It's scientifically proven that the lean and light body of East Africans favour them against the rest of the world.
    * Similarly Jamaica is specialised in short distance running. Along with the hardwork that they put in, they also have a genetic advantage which is attributed to the ACE gene that is present in their body which results in larger than average heart capable of pumping highly oxygenated blood to muscles quicker than the average human.
    * Cubans win the highest number of medals in Boxing. They are taught boxing from their very young age as an after school activity. This helps them to pick the best out of a larger pool of people. Also practicing it from a younger age helps them to shape better boxers when compared to other countries.
    * In case of Netherlands, they dominate the Speed skating competitions in Winter Olympics. The Dutch tend to be relatively tall with an average height above 6 feet, which is an advantage in speed skating because it allows for taking long strides. Also, since childhood, Dutch skaters train with excellent instructors with the best skating equipment in the world. 
    
> ### 3rd Visualization-I: Gender Equality at Olympics
![figure4](https://github.com/nikhilarosekuruvilla/Olympic-Games-Analysis-1976-2016/blob/master/Visualizations/Male%20vs%20Female%20medal%20winners%20over%20the%20years.png)
1. Over time, the number of medals for females have increased  which in turn says number of events for females have increased while the number of events for males have remained consistent.
    * In the early days of the Olympic Games, many countries limited the amount of female competitors they would send because they would incur the cost of paying for a chaperone, which was not necessary for the male athletes.
    * The International Olympic Committee then took initiative to bring gender equality in Olympic events and formed Women in Sports Commission as a part of this effort.
    * This resulted in an increase in the number of events allowing female participation, showing that women are getting more respect and acceptance at Olympic games when compared to older times. 
    
> ### 3rd Visualization-II: Sex ratio of USA, Russia & Germany at Olympics

![figure3](https://github.com/nikhilarosekuruvilla/Olympic-Games-Analysis-1976-2016/blob/master/Visualizations/Comparison%20of%20Male:Female%20Participant%20ratio%20at%20Olympics.png)
1. USA, Russia and Germany are three of the top countries who perform well at both Summer and Winter Olympics. Comparing their sex ratios to the overall sex ratio at the Olympic games, we can see that their sex ratios are comparitively lower than the overall value.
     * This is interesting because one of the reasons why they do well at the games could be because they train their athletes without any discrimination on gender and give oppurtunity to people with talents.
    
## Future Scope
* It will be interesting to see, what differences Olympic games went through when comparing the last two decades to the games in the first decades of Modern Olympics.
