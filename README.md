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
![ss2](mdpgl.png)

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
![ss1](op.png)
## RESULT:
Thus the given Markov Decision Process(MDP) problem is represented in the following ways.

Text representation,
Graphical representation,
Python - Dictonary representation.
