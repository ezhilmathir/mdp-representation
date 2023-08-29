# <p align="center"> MDP REPRESENTATION </p>

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

  1. Text representation
  2. Graphical representation
  3. Python - Dictonary representation

## PROBLEM STATEMENT:

### Problem Description:
Imagine a game where you are managing a plant's health.The plant can be either in good health or welted state.

### State Space:
{W,S,H} -> {0,1,2}

where,
- W -> Wilted state
- S -> Stationary(idle)
- H -> Healthy
### Sample State:
H -> 2<br>
The plant is healthy.

### Action Space:
{W,D} -> {0,1}
 where,
 - W -> Water the plant
 - D -> Do nothing

### Sample Action:
W -> 0<br>
The plant is watered

### Reward Function:
R = { +1,when water is poured,<br>
       0,otherwise}

### Graphical Representation:
![image](https://github.com/SanjayKumarAIML/mdp-representation/assets/93427246/1a25dfb5-3e0f-4076-8b4b-6dc41a235764)


## PYTHON REPRESENTATION:
```py
P = {
    0:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,0,0.0,True)]
    },
    1:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,2,1.0,True)]
    },
    2:{
        0: [(1.0,2,0.0,True)],
        1: [(1.0,2,0.0,True)]
    }
}
```
## OUTPUT:
```
{0: {0: [(1.0, 0, 0.0, True)], 1: [(1.0, 0, 0.0, True)]},
 1: {0: [(1.0, 0, 0.0, True)], 1: [(1.0, 2, 1.0, True)]},
 2: {0: [(1.0, 2, 0.0, True)], 1: [(1.0, 2, 0.0, True)]}}
```

## RESULT:
Thus the given Markov Decision Process(MDP) problem is represented in the following ways.

  1. Text representation
  2. Graphical representation
  3. Python - Dictonary representation

