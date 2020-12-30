**Predicting Whiff Rate**



**Whiff Rate** in baseball is the quotient of dividing swing and miss by total amount of swings. The more a pitcher can get a batter to swing and miss at his pitches the better he would be at preventing overall offense. Runs almost exclusively happen when batters put the ball in play through hits, errors, and even outs such as; sac flies, ground balls, and bunts. The less contact a pitcher can give up the less amount of runs he will give up presumably.



This project was done to determine what pitching metric based off Statcast data is best at preventing contact with a baseball. We look at velocity and spin rate of the six basic pitches; four seam fastball, two seam fastball, slider (& cutter), changeup, curveball and splitter. The model I ran was a Random Forest as I wanted every tree to be grown simultaneously to avoid any bias error. 



When I attempted to plot a decision tree from the random forest model it became jumbled as there were many different factors that went into creating the model. I will have to create specific predictive modeling projects for each pitch to fully determine the extent of each pitch's ability to miss bats.



The below chart depicts the importance of each feature for whiff rate based off the model I ran



![Image of Whiff Rate Variable Importance](https://raw.githubusercontent.com/Chrisboatto/Predicting-Whiff-Rate/main/Whiff%20Variable%20Importance.png)



