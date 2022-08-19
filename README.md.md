
# Investigate Soccer Dataset

The soccer dataset was sourced from kaggle website [Link](https://www.kaggle.com/datasets/hugomathien/soccer)

## Introduction

The relationship between these two tables is that the height and weight of a player may be connected to some attributes as documented in the players' attributes. For instance, the heading accuracy for a taller person may likely head a ball into or prevent it from entering the goal post. Also, height may be implicated in assessing a player's potential towards his role as a defender, goalkeeper, or midfielder. In addition, the BMI estimated from the height and weight of a player influence the sprint speed, stamina. Both height and weight may contribute to the overall rating of a player. To make this claims worthy, it is necessary to use data to tell this story.

Dependent variable(s): overall_rating, potential, heading_accuracy, sprint_speed, stamina, strength independent variable(s): Height and weight



### Aim
The purpose of this investigation is to understand how the height and weight of Players, having two different identification numbers (player_api_id and FiFa_id), effect on their attribute’s qualities, which may consequently impact the performance of the team they represent.



### Question(s) for Analysis
1. What is the relationship between the height and some players' attributes such as overall_rating, potential, heading_accuracy and sprint_speed?
2. What is the relationship between weight and some players' attributes such as overall_rating, potential, heading_accuracy and sprint_speed?


# Gathering tools for analysis


```python
# Upgrade pandas to use dataframe.explode() function. 
!pip install --upgrade pandas==0.25.0

#import
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline
```

# Findings on Question 1
### Result
- From the analysis, the mean height levels: short, medium, and tall players are 164.39, 172.97, and 183.55 cm, respectively. 
- The result revealed that tall players have higher heading accuracy and strength, but short players have better sprint speed and stamina. 
- Furthermore, results shows that short players have higher overall rating than medium and tall players.  
- There is only a slight difference between the players of medium and tall heights in terms of their potentials.
- From the pie chart, the player heights are 31, 33, and 35% for short, medium, and tall players, respectively. Hence, there are taller player than short players.


### Discussion 

- This result is also supported by the football observatory report. According to the football observatory report, there is no correlation between the average height of players in soccer teams and their performance in soccer match. Rather, the gaps observed in their overall rating and potential, as regards to players performance, may possibly be attributed to the diverse players' trainings, practice, and approaches engaged in the socceer game.

- Although, tall players may be preferred for the position of goal keepers or midfield players for the purpose of accurate heading of ball and catching the ball, the shorter players have better sprint speed and stamina that give them a better advantage. 

- In summary, short players may complement the tall ones, however, it is necessary that both the tall and short players train to become more professional, as such these players representing their respective team will be well distinguished in excellence.


# Findings on Question 2

### Result 
- From the pie chart, the percentage of players categorized based on their BMI levels as underweight, normal, overweight, and obesed are 19, 23, 26, 32%, respectively. 
- The weight of player as it affects the players attibutes or perfomance in each football match may not give substantial information. For this reason, the body mass index (BMI) was used.
- Players who are obesed have higher overall rating, possibly due to higher sprint speed, strength, heading accuracy. However, those with normal BMI, showed better potential based on their heights.

### Discussion 
- According to CDC, high BMI indicates high body fatness, but it does not diagnose the body fatness or health of an individual. Also, it must be noted that the heights of players affect BMI while other factors, especially bone index, contribute to the weight of a player. The result of this analysis reveals that obese players have high heading accuracy and strength. 

- The later qualities determine the position of players as an offensive or defensive player in each soccer match as well as the player's efficiency in such position. The observation from is this analysis is supported by the report of Dengel et al. (2020) on the body composition and bone mineral density of national football league players. 

- According to Dengel et al. (2020), there is a relationship between the bone density of players and their body fat. Hence, the obese player has features that are required, however, the weight (as reflected in BMI) may not provide a robust means of assessing a player's attribute wholesomely, even though players are **not expected to be fat.

- The age of players is necessary in deciding whether a player is obese or not. Besides the age of the players, players are also encouraged to take calcium and magnesium supplement for strong bones, considering their strenuous physical activity. These calcium and magnesium deposit in the bone and may increase the bone index, and consequently, the weight of players. 
- According to Dobrowolski et al. (2020), calcium intake is one of the determining factors in bone mass formation and influences bone index/density. The combination of calcium rich-meal or supplement and the short heights of players may produce high BMI such that a player may be tagged 'obese'.


Finally, the calorie intake, in addition to the supplement, must be taken into cognisance as soccer players require lots of energy which are majorly carbohydrates for their high physical activities.

# Possible further research

1.	Considering the age changes across the various years of data collection, how does the age of a player affect the height of players?
2.	Considering the high physical activities of soccer players, what type of dieting have any impact on the height of soccer players?

# Limitations identified
1.	The age of the individual player gives a clearer definition of obesity. Note that BMI is further classified (into BMI for children and BMI for adult) depending on the age. Unfortunately, this analysis did not factor in the age of the players.
2.	Medical information such as calcium and magnesium levels may be included.
3.	Information on whether the player is on any calcium/magnesium supplement may be included.
4.	Information on calorie/carbohydrate intake for individual player can be included.


```python

```
