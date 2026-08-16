# 485. Max Consecutive Ones

* **Platform**: LeetCode
* **Difficulty**: Easy
* **Language**: C++
* **Problem Link**: [Max Consecutive Ones](https://leetcode.com/problems/max-consecutive-ones/)

## 🧠 AI Complexity Analysis

* ⏱️ **Time Complexity**: `O(N)`
* 💾 **Space Complexity**: `O(1)`
* 🧩 **Pattern**: `Arrays & Hashing`
* 💡 **Intuition**: Iterates through input elements to compute result efficiently.
* 🎯 **Edge Cases**: Handles standard constraints, empty inputs, and boundary values.
* 🤖 *Engine: Static AI Engine*

## 🚀 What You Should Try Next

* 🎯 **Recommended Practice**: [Group Anagrams](https://leetcode.com/problems/group-anagrams/) (Medium)
* 💡 **Why Try Next**: Master hash map grouping with string keys.

## Solution Code
```cpp
class Solution {
public:
    int findMaxConsecutiveOnes(vector<int>& nums) {
        int maxi=0;

        int i=0;
        int ones=0;
        while(i<nums.size())
        {
          
            if(nums[i]==1)
            {
                ones++;
            }

```
