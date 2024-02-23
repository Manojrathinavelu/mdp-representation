# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

Text representation,
Graphical representation,
Python - Dictonary representation.

## PROBLEM STATEMENT:

### Problem Description
To develope a game application. The role of the agent is to promote if the level is cleared or depromote if the game is lost.

### State Space
{L1,L2,L3}->{0,1,2}
- L1-> Level 1
- L2-> Level 2
- L3-> Level 3

### Sample State
L1-> 0-> Level 1

### Action Space
{W,L}->{0,1}
- W-> Winning
- L-> Loosing

### Sample Action
W-> 0-> Winning

### Reward Function
```
R= {
    +1, if we come closer to winning
    +0, otherwise

```
### Graphical Representation
![Screenshot 2024-02-23 102140](https://github.com/Manojrathinavelu/mdp-representation/assets/119560395/d8fb0667-943e-4541-968c-7600d6e00360)

## PYTHON REPRESENTATION:
```py
T = {
    0 : {
        0 : [(1.0, 1, 1.0, True)],
        1 : [(1.0, 0, 0.0, False)]
    },
    1 : {
        0 : [(1.0, 2, 1.0, True)],
        1 : [(1.0, 0, 0.0, False)]
    },
    2 : {
        0 : [(1.0, 2, 1.0, True)],
        1 : [(1.0, 1, 0.0, False)]
    }
}

T
``````

## OUTPUT:
![WhatsApp Image 2024-02-23 at 10 32 56_ff552975](https://github.com/Manojrathinavelu/mdp-representation/assets/119560395/2d29d4f3-3459-4ff1-9338-b9d24dc1adae)


## RESULT:
Thus the given Markov Decision Process(MDP) problem is represented in the following ways.

Text representation,
Graphical representation,
Python - Dictonary representation.
