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
name: Nakid, Miss. Maria ("Mary")
Pclass: 3
Age: 1.0
Sex: female
Fare: 15.74
Embarked: C
```
**Card 2**
```
name: Calic, Mr. Jovo
Pclass: 3
Age: 17.0
Sex: male
Fare: 8.66
Embarked: S
```
**Card 3**
```
name: Calic, Mr. Petar
Pclass: 3
Age: 17.0
Sex: male
Fare: 8.66
Embarked: S
```
**Card 4**
```
name: O'Brien, Mrs. Thomas (Johanna "Hannah" Godfrey)
Pclass: 3
Age: nan
Sex: female
Fare: 15.5
Embarked: Q
```
**Card 5**
```
name: Long, Mr. Milton Clyde
Pclass: 1
Age: 29.0
Sex: male
Fare: 30.0
Embarked: S
```
**Card 6**
```
name: Vestrom, Miss. Hulda Amanda Adolfina
Pclass: 2
Age: 14.0
Sex: female
Fare: 400.18
Embarked: S
```

---
### GM Guide

> **Hint:** GM Hint: Refer to the box plot above. The forged card has a fare that doesn't match its class - either much higher or much lower than typical for that class. Players should compare each card's fare with the distribution shown in the chart for that card's class.
> **Answer:** [[REVEAL_ANSWER]]The forged card: 2nd class (Pclass=2) but paying £400.18, which doesn't match typical 2nd class fares (£10.50-73.50). **(In this game, this card is Card 6)**[[END_REVEAL]]
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
Name: Braund, Mr. Owen Harris
Pclass: 3
Age: 22
Sex: male
Fare: 7.25
Embarked: S
```
**Card 2**
```
Name: Danoff, Mr. Yoto
Pclass: 3
Age: 27
Sex: male
Fare: 7.9
Embarked: S
```
**Card 3**
```
Name: Emanuel, Miss. Virginia Ethel
Pclass: 3
Age: 5
Sex: female
Fare: 12.47
Embarked: S
```
**Card 4**
```
Name: Johnson, Mr. William Cahoone Jr
Pclass: 3
Age: 19
Sex: male
Fare: 0.0
Embarked: S
```

---
### GM Guide

> **Hint:** Use the survival charts above to infer the 4-digit lifeboat code.
> **Answer:** [[REVEAL_ANSWER]]0010[[END_REVEAL]]
> **Obtain:** **Temporal Coordinate Fragment 3** hidden within the lifeboat control panel.

---
## Letters from a Stowaway

**Story:** Story

**Task:** Instructions

### Letters from the Stowaway 

**Plaintext Letter**```Hello, this is unencrypted text
```
**Encrypted Letter**```amix, ix hqivh aq lu uvrsdwaue
```
### Possible suspects 

---
## Game End

Congratulations! You've collected all 5 coordinate fragments, restarted the time machine, and successfully escaped from 1912 at the moment the Titanic sank.
