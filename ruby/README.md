Write a score keeping application. It must take a formated string which lists in order how many points a given person was given or lost. It then must output the total number of points each person has accrued to another formatted string. Specifically:

- The input string will always be valid.
- Names will only ever contain letters.
- Scores can go negative.
- Items in the list will be separated by new line characters.
- Names will be followed by a colon and a single space.
- Scores/points must be preceded by a + or - depending on whether it is positive or negative.
- Zero shouldn't have a sign before it.
- The output names should be in alphabetical order.

Here is an example input string:

```
Heather: +4
Chen: +10
Helga: +22
Heather: -7
Chen: +2
Balthazar: -1
```

Here is the output that string should generate:

```
Balthazar: -1
Chen: +12
Heather: -3
Helga: +22
```
