Alice and Bob are participating in a dice tournament as a team.
After the tournament, the points they have achieved as a team must be calculated.
The following applies:
- One pair: sum of the two numbers
- Two pairs: sum of the four numbers
- Three of a kind: sum of the three numbers
- Four of a kind: sum of the four numbers
- Full House: 25 points
- Small Straight (4-card straight): 30 points
- Big Straight (5-card straight): 40 points
- Five of a Kind: 50 points
- *otherwise*: 0 points

The result of their test round was as follows:
```
Alice 1 4 2 5 2
Bob 5 5 3 5 3
Alice 2 4 6 5 3
Bob 2 5 2 5 2
```

To calculate their scores, they now go through all the results:
- `Alice 1 4 2 5 2` contains one pair: *2* *2*; that gives 4 points (sum of the numbers)
- `Bob 5 5 3 5 3` contains a full house: *5* *5* *5* *3* *3*; this gives 25 points
- `Alice 2 4 6 5 3` contains a big straight: *2* *3* *4* *5* *6*; this gives 40 points
- `Bob 2 5 2 5 1` contains two pairs: *2* *2* *5* *5*; this results in 14 points (sum of the numbers)

- Their total score would therefore be 83 points

How many points did Alice and Bob each earn in the tournaments in `input1.txt`, `input2.txt`, and `input3.txt`?