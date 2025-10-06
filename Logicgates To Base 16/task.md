Walter has devised a system for encrypting hexadecimal numbers.
To do this, he converts a hexadecimal number into a binary number and thinks of a few values (0 or 1) which he assigns to variables.
He has written down his variables at the top.
He goes through the binary number backwards and then starts from the top to think of a logic gate with the variables for each digit of the binary number.
If the digit of the binary number is 0, then the output of the logic gate is also 0, and if the binary number is 1, the output is 1.
He always writes this logic gate at the very bottom of his file.

If he wants to encrypt the 3 from the hexadecimal system, he could write:
```
a 1
b 0
c 1
a OR b
b NAND c
a NOR c
```

This can be read as follows:
- he sets `a` and `c` to `1` and `b` to `0`
- the last digit of the binary number is `a OR b` (`1 OR 0`), which equals 1
- The penultimate digit of the binary number is `b NAND c` (`0 NAND 1`), which equals 1
- The third-to-last digit of the binary number is `a NOR c` (`1 NOR 1`), which equals 0
- Read backwards, you get the binary number `011`, which equals the decimal number `3`

- If he now converts the 3 from the decimal system to the hexadecimal system, he gets `3` 

***An overview of the logic gates can be found in the file `logicgates.md`***

What are the encrypted hexadecimal numbers from the files `input1.txt`, `input2.txt`, and `input3.txt`?