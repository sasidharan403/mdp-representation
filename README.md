# MDP REPRESENTATION

## AIM:
The representation of real world scenario using Markov Decision Process by stating all the states,actions and environment with respective rewards.

## PROBLEM STATEMENT:
To develop a game which will promote to other level,when the agent complete its task correctly.
### Problem Description
If the agent unable to complete the given task,then there is no promotion to other level,when it reaches the final level,it will recieve a reward.

### State Space
{L1,L2,L3}--->{0,1,2}
### Sample State
L1--->{0}

### Action Space
Moving Left(1)

Stay in the same level(0)

### Sample Action
Stay in the same level(0)

### Reward Function
+1(When it reaches the goal state or final level)

### Graphical Representation
![image](https://github.com/user-attachments/assets/1530363d-7e3c-4843-9221-4f363143adde)



## PYTHON REPRESENTATION:
~~~
NAME : A.sasidharan
REG NO : 212221240049

P = {
    0:{
        0: [(0.44,0,0,True),(0.13,1,0,False)],
        1: [(0.13,1,0,False),(0.44,0,0,True)]
    },
    1:{
        0: [(0.44,1,0,False),(0.13,2,1,True)],
        1: [(0.13,2,1,True),(0.44,1,0,False)]
    },
    2:{
        0: [(0.44,2,1,True),(0.13,1,1,False)],
        1: [(0.13,1,1,False),(0.44,2,1,True)]
    }
}


~~~

## OUTPUT:
![image](https://github.com/user-attachments/assets/e59fea22-9c8a-4a64-9a80-501a859af230)





## RESULT:
Therefore an MDP representation has been created for a real world scenario with all the states, actions and rewards.
