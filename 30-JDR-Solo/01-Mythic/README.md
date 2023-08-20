# Mythic

## Overview
https://www.drivethrurpg.com/product/422929/Mythic-Game-Master-Emulator-Second-Edition  

## Concepts
### Fate Chart
Table which allows to answer to a Yes/No question.  

Roll a D100 and according to the result the answer can be:
- Yes
- Exceptional Yes
- No
- Exceptional No

The table is based on:
- Probability of the event occurrence
- Current Chaos Factor

For each combination, you have 3 thresholds a < b < c (aBc)  to determine the answer :
- =< a : Exceptional Yes
- =< b : Yes
- =< c : No
- \> c : Exceptional No

"X" value means it can't occur.  

**Important**:
- Questions have to be oriented the way that Yes answer bring more actions


<img src="img/fate_chart.jpg" width="600px">



### Chaos Factor
Mythic's way of simulating tempo changes and representing how the PC has over the actions.  

It uses a value between 1 and 9. 
The starting value is **5**.  

The higher, the more Mythic generates active elements (random events, unexpected scenes) and Yes answers for Fate Questions.  

The Chaos Factor changes after each scene and:
- Increase by 1 if the user didn't have control during the last scene  
- Decrease by 1 if the user had control during the last scene  

### Scene
Mythic divides adventures into Scenes.  
A scene is a discrete portion of the adventure that encapsulates an important moment or event.  

When a scene ends:
- Update the thread list
- Update the characters List
- Adjust the Chaos Factor


### Random Event


### Lists
Lists allowed to follow the characters and threads to be re-used later by random events.

- **Thread Lists**  
    List the adventure objectives/goals

- **Characters Lists**  
    List the important NPCs encountered


### Meaning Table
Tables used to add details to your adventure without asking Fate questions.
Especially when you don't have expectation about upcoming events.  


### Elements Meaning Actions

## Ask Fate Questions
Try to not ask more than 2 questions on a same detail. 1 is the best as much as possible.    

### Fate Chart

1. Ask a question where yes bring an active situation
2. Choose the probability to get a Yes to your question
3. Roll 2d10 
4. Check the result in the Fate chart according the Chaos Factor
5. If you get: 
    - A double figure 
    - This figure is =\< Chaos Factor  

    Then a random event occurs

### Fate Check
Simple alternative way to ask Fate questions.  

1. Roll 2d10
2. sum the results
3. Add modifiers according to the occurence probability and chaos factor
4. Check according the answer table

**Note**: Value > 20 \<2 are not considered as exceptional yes/no, but simple yes/no.  


<img src="img/fate_check.jpg" width="600px">
