# Solution Template

Use this template when adding new solutions to the repository.

## For Python Solutions

```python
# LeetCode #[Number]: [Problem Name]
# Difficulty: [Easy/Medium/Hard]
# Link: https://leetcode.com/problems/[problem-name]/
#
# Problem Description:
# [Brief description of the problem]
#
# Solution Approach:
# [Explain your approach and algorithm]
#
# Time Complexity: O(?)
# Space Complexity: O(?)

class Solution:
    def problemName(self, param1, param2):
        """
        :type param1: Type
        :type param2: Type
        :rtype: ReturnType
        """
        # Your solution here
        pass

# Test cases
if __name__ == "__main__":
    solution = Solution()
    # Add test cases
    print(solution.problemName(test_input))
```

## For Java Solutions

```java
// LeetCode #[Number]: [Problem Name]
// Difficulty: [Easy/Medium/Hard]
// Link: https://leetcode.com/problems/[problem-name]/
//
// Problem Description:
// [Brief description of the problem]
//
// Solution Approach:
// [Explain your approach and algorithm]
//
// Time Complexity: O(?)
// Space Complexity: O(?)

class Solution {
    public ReturnType problemName(Type param1, Type param2) {
        // Your solution here
        return result;
    }
    
    // Test
    public static void main(String[] args) {
        Solution solution = new Solution();
        // Add test cases
        System.out.println(solution.problemName(testInput));
    }
}
```

## For C++ Solutions

```cpp
// LeetCode #[Number]: [Problem Name]
// Difficulty: [Easy/Medium/Hard]
// Link: https://leetcode.com/problems/[problem-name]/
//
// Problem Description:
// [Brief description of the problem]
//
// Solution Approach:
// [Explain your approach and algorithm]
//
// Time Complexity: O(?)
// Space Complexity: O(?)

class Solution {
public:
    ReturnType problemName(Type param1, Type param2) {
        // Your solution here
        return result;
    }
};

// Test
int main() {
    Solution solution;
    // Add test cases
    return 0;
}
```

## For JavaScript Solutions

```javascript
// LeetCode #[Number]: [Problem Name]
// Difficulty: [Easy/Medium/Hard]
// Link: https://leetcode.com/problems/[problem-name]/
//
// Problem Description:
// [Brief description of the problem]
//
// Solution Approach:
// [Explain your approach and algorithm]
//
// Time Complexity: O(?)
// Space Complexity: O(?)

/**
 * @param {Type} param1
 * @param {Type} param2
 * @return {ReturnType}
 */
var problemName = function(param1, param2) {
    // Your solution here
    return result;
};

// Test cases
console.log(problemName(testInput));
```

## General Guidelines

1. Always include:
   - Problem number and name
   - Difficulty level
   - Link to the problem
   - Problem description
   - Your approach/algorithm
   - Time and space complexity

2. Add meaningful comments explaining complex logic

3. Include test cases to verify your solution

4. Consider edge cases in your implementation

5. Update the category README.md with the problem name and link
