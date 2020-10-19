#### https://leetcode.com/problems/contains-duplicate/
```js
/**
 * @param {number[]} nums
 * @return {boolean}
 */
var containsDuplicate = function(nums) {
    let set = new Set(nums)
    return (set.size < nums.length)
};
```

