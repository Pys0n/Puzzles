The math teacher gave his class a math test.
For this, he received calculations from each student in the format: `result = integer operator integer`.
The operator is `plus`, `minus`, `times`, or `divided by`, which stand for `+`, `-`, `*`, and `/`.
To find out how well the entire class did, he wants to calculate each student's score and then add up all the students' scores to get a total score.

The input file with the students' calculations might look like this:
```
Alice
4 = 2 times 2
3 = 3 minus 1
Bob
3 = 0 plus 4
5 = 10 divided by 5
```

The approach for the sample input file:
- Find the first line with a calculation; check whether 4 = 2 times 2; if so, increase the total score by 1.
- Find the second line with a calculation; check whether 3 = 3 minus 1; if so, increase the total score by 1
- Find the third line with a calculation; check whether 3 = 0 plus 4; if so, increase the total score by 1
- Find the fourth row with a calculation; check whether 5 = 10 divided by 5; if so, increase the total score by 1

- The total score for the class would be 1. 

What are the total scores for the classes from the files `input1.txt`, `input2.txt`, and `input3.txt`?