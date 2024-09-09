# MDP REPRESENTATION

## AIM:
To represent any one real-world problem in MDP form.

## PROBLEM STATEMENT:
To develop a game application the role of the agent is to promote if the level is cleared or depromote if the game is loss

### Problem Description


### State Space
{A1,A2,A3}--> {0,1,2}
A1--> LEVEL 1
A2--> LEVEL 2 
A3--> LEVEL 3

### Sample State
A1--> 0 --> LEVEL 1

### Action Space
{W,L}-->{0,1}
W-->True
L-->False

### Sample Action
W--> 0 --> True

### Reward Function
R = { +1 , if we come closer to the winning
       0 , if not

### Graphical Representation
![rllnn](https://github.com/user-attachments/assets/fc83f34f-9d73-4dc3-be81-79c59740c45b)


## PYTHON REPRESENTATION:
```
P = {
    0:{
        0: [(0.77,0,0,True),(0.23,1,0,False)],
        1: [(0.23,1,0,False),(0.77,0,0,True)]
    },
    1:{
        0: [(0.77,1,0,False),(0.23,2,1,True)],
        1: [(0.23,2,1,True),(0.77,1,0,False)]
    },
    2:{
        0: [(0.77,2,1,True),(0.23,1,1,False)],
        1: [(0.23,1,1,False),(0.77,2,1,True)]
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/7de4f369-9398-4534-846b-d7b3c5175ce5)


## RESULT:
Thus the given real world problem is successfully represented in a MDP form .

