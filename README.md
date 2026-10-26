# ExpNo 5 : Implement Simple Hill Climbing Algorithm 
## Name: Sai Hrishi M             
## Register Number:             

## Aim:
Implement Simple Hill Climbing Algorithm and Generate a String by Mutating a Single Character at each iteration 

## Theory: 

Hill climbing is a variant of Generate and test in which feedback from test procedure is used to help the generator decide which direction to move in search space.
Feedback is provided in terms of heuristic function

## Algorithm:

1.Evaluate the initial state.<br><br>
2.If it is a goal state then return it and quit. Otherwise, continue with initial state as current state.<br><br>
3.Loop until a solution is found or there are no new operators left to be applied in current state. <br><br>
4.Select an operator that has not yet been applied to the current state and apply it to produce a new state.<br><br>
5.Evaluate the new state:<br><br>
 i) if it is a goal state, then return it and quit<br>
 ii) if it is not a goal state but better than current state then make new state as current state<br>
 iii) it is not better than current state then continue in the loop<br>
    

## Steps Applied:

### Step-1

Generate Random String of the length equal to the given String

### Step-2

Mutate the randomized string each character at a time

### Step-3

Evaluate the fitness function or Heuristic Function

### Step-4:

Loop Step -2 and Step-3  until we achieve the score to be Zero to achieve Global Minima.


## Sample Input and Output

Sample String: Artificial Intelligence

### Output:

Score: 643  Solution :  8RzF:oG ]%;CPORRMe!zGvk<br>
Score: 609  Solution :  8RzF:oG ]%;CPqRRMe!zGvk<br>
Score: 604  Solution :  8RzF:oG ]%;CPqRRMe!zGqk<br>
Score: 594  Solution :  8RzF:oG ]%;CPqRRWe!zGqk<br>
Score: 551  Solution :  8RzF:oGK]%;CPqRRWe!zGqk<br>
Score: 551  Solution :  8RzF:oGK]%;CPqRRWe!zGqk<br>
Score: 551  Solution :  8RzF:oGK]%;CPqRRWe!zGqk<br>
Score: 551  Solution :  8RzF:oGK]%;CPqRRWe!zGqk<br>
Score: 551  Solution :  8RzF:oGK]%;CPqRRWe!zGqk<br>
....................................................<br>
..................................................<br>
................................................<br>
Score: 1  Solution :  Artificial Intelligencf<br>
Score: 1  Solution :  Artificial Intelligencf<br>
Score: 1  Solution :  Artificial Intelligencf<br>
Score: 1  Solution :  Artificial Intelligencf<br>
Score: 0  Solution :  Artificial Intelligence<br>


### Output:

<img width="543" height="768" alt="image" src="https://github.com/user-attachments/assets/357b7caa-21dc-4716-8fcb-16a907b8034a" />

### Result:

Thus, we have successfully Implement Simple Hill Climbing Algorithm and Generated a String by Mutating a Single Character at each iteration
