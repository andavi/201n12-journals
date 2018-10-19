# Day 13

Today we talked about some advanced JavaScript topics. I actually enjoyed this part of class. My favorite array methods are map, reduce, and filter. If you want to do a deep copy of a two-dimensional array in one line do this: 

`const arrCopy = arr.map(row => [...row]);`

Neat.

```
> const arr = [[1,2,3],[4,5,6],[7,8,9]]
undefined
> arr
[ [ 1, 2, 3 ], [ 4, 5, 6 ], [ 7, 8, 9 ] ]
> const arrCopy = arr.map(row => [...row]);
undefined
> arrCopy
[ [ 1, 2, 3 ], [ 4, 5, 6 ], [ 7, 8, 9 ] ]
> arr[1][1] = 'no'
'no'
> arr
[ [ 1, 2, 3 ], [ 4, 'no', 6 ], [ 7, 8, 9 ] ]
> arrCopy
[ [ 1, 2, 3 ], [ 4, 5, 6 ], [ 7, 8, 9 ] ]
```