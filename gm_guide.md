# The Temporal Rift on the Titanic: GM Guide

**Player Role:** You are a team of time travelers.
**Final Goal:** Before the ship sinks, find 5 missing 'temporal coordinate fragments'.

--- 
## Challenge 1: Purser's Office (Find the Anomaly)

**Story:** You've just boarded and been caught as stowaways. On the desk is a stack of passenger registration cards. You must identify the 'forged' card among them.

**Task:** Out of the following 6 passenger cards, which one is statistically impossible?

![Box Plot](hint\challenge_1_boxplot.png)

### Passenger Cards (Show to Players)

**Card 1**
```
name: Williams, Mr. Howard Hugh "Harry"
Pclass: 3
Age: nan
Sex: male
Fare: 8.05
Embarked: S
```
**Card 2**
```
name: Carter, Miss. Lucile Polk
Pclass: 1
Age: 14.0
Sex: female
Fare: 120.0
Embarked: S
```
**Card 3**
```
name: Lefebre, Miss. Jeannie
Pclass: 3
Age: nan
Sex: female
Fare: 25.47
Embarked: S
```
**Card 4**
```
name: Warren, Mrs. Frank Manley (Anna Sophia Atkinson)
Pclass: 1
Age: 60.0
Sex: female
Fare: 6.95
Embarked: C
```
**Card 5**
```
name: Panula, Master. Juha Niilo
Pclass: 3
Age: 7.0
Sex: male
Fare: 39.69
Embarked: S
```
**Card 6**
```
name: Peters, Miss. Katie
Pclass: 3
Age: nan
Sex: female
Fare: 8.14
Embarked: Q
```

---
### GM Guide

> **Hint:** GM Hint: Refer to the box plot above. The forged card has a fare that doesn't match its class - either much higher or much lower than typical for that class. Players should compare each card's fare with the distribution shown in the chart for that card's class.
> **Answer:** [[REVEAL_ANSWER]]The forged card: 1st class (Pclass=1) but paying £6.95, which is much lower than typical 1st class fares (£5.00-512.33). **(In this game, this card is Card 4)**[[END_REVEAL]]
> **Obtain:** **Temporal Coordinate Fragment 1** hidden under the forged card.

---
## Decipher the Lifeboat Code

**Story:** The lifeboat lock requires a 4-digit code based on passengers' survival predictions.

**Task:** Predict which of the 4 passengers survived (1) or perished (0). Use the survival clues provided.

![Hint Chart 1](hint/challenge_3_sex_pclass.png)

![Hint Chart 2](hint/challenge_3_age_group.png)

### Passenger Cards (Show to Players)

**Card 1**
```
Name: Mionoff, Mr. Stoytcho
Pclass: 3
Age: 28
Sex: male
Fare: 7.9
Embarked: S
```
**Card 2**
```
Name: Olsen, Mr. Ole Martin
Pclass: 3
Age: 29
Sex: male
Fare: 7.31
Embarked: S
```
**Card 3**
```
Name: Cribb, Mr. John Hatfield
Pclass: 3
Age: 44
Sex: male
Fare: 16.1
Embarked: S
```
**Card 4**
```
Name: Allison, Master. Hudson Trevor
Pclass: 1
Age: 1
Sex: male
Fare: 151.55
Embarked: S
```

---
### GM Guide

> **Hint:** Use the survival charts above to infer the 4-digit lifeboat code.
> **Answer:** [[REVEAL_ANSWER]]0001[[END_REVEAL]]
> **Obtain:** **Temporal Coordinate Fragment 3** hidden within the lifeboat control panel.

---
## Letters from a Stowaway

**Story:** Story

**Task:** Instructions

### Letters from the Stowaway 

**Plaintext Letter**```This is my plaintext letter
```
**Encrypted Letter**```This is my encrypted letter
```
### Possible suspects 

---
## Game End

Congratulations! You've collected all 5 coordinate fragments, restarted the time machine, and successfully escaped from 1912 at the moment the Titanic sank.
