##### Chapter 6 – day 1

1. Write a function corners() that will take two parameters m and n and returns a string with m+1 plus signs each of which 
are separated by n dashes. So corners(3,2) would return +--+--+--+ and corners(1,5) would return +-----+

2. Write a function vertical() that will take two parameters m and n and returns a string with m+1 vertical bars each of 
which are separated by n spaces. So vertical(3,2) would return 
```
|  |  |  |
```
and vertical(1,5) would return 
```
|     |
```

3. Write a function boxes(m,n,o,p) which will return a string that is a large box divided into smaller boxes. The smaller boxes should be n dashes wide and p vertical dashes high. The large box is m of the smaller boxes wide and o of the smaller boxes high.  

box(3,4,2,5) 

should return the string that when printed that gives 3 boxes horizontally with width 4 dashes and 2 boxes vertically with height 5.

```
+----+----+----+
|    |    |    |
|    |    |    |
|    |    |    |
|    |    |    |
|    |    |    |
+----+----+----+
|    |    |    |
|    |    |    |
|    |    |    |
|    |    |    |
|    |    |    |
+----+----+----+
```

This wouldn't be a bad place to comment your code:
def boxes(m, n, o, p):
\# m is the number of small boxes horizontally.
\# n is the number of horizontal dashes at the top of a small box.
\# o is the number of small boxes vertically.
\# p is the height of a small box in vertical dashes.
