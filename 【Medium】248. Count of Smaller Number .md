> Give you an integer array (index from 0 to n-1, where n is the size of this array, value from 0 to 10000) and an query list. For each query, give you an integer, return the number of element in the array that are smaller than the given integer.. (The array may not fully filled by elements)
>
> **Notice:** 
> 
> We suggest you finish problem Segment Tree Build and Segment Tree Query II first.
>

**Example:** 

For array [1,2,7,8,5], and queries [1,8,5], return [0,4,2]

## 解题思路

结合建树和查询：

 + [201. Segment Tree Build](https://github.com/ForestCold/Algorithms/edit/master/%E3%80%90Medium%E3%80%91201.%20Segment%20Tree%20Build.md)
 + [247. Segment Tree Query II](https://github.com/ForestCold/Algorithms/blob/master/%E3%80%90Medium%E3%80%91247.%20Segment%20Tree%20Query%20II.md)

这题的follow up：

 + [249 Count of Smaller Number before itself ](https://github.com/ForestCold/Algorithms/blob/master/%E3%80%90Hard%E3%80%91249.%20Count%20of%20Smaller%20Number%20before%20itself.md)
 

## 时间空间复杂度

O(logn)

*n为Max-Min*
