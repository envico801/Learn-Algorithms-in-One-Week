# ALAIO - Learn algorithms in one week - alvin zablan

## Questions

### 1. The Complete Guide to Big O Notation & Complexity Analysis for Algorithms

#### Part 1 of 2

Q: Why do we use Big 0?  
A: It's a framework we can use to judge which solutions are "better" than others.

Q: What makes a solution "better"?  
A: We prefer solutions that use the least resources:  
1.time (duration)  
2.space (memory)

Q: How do we control for differences in computer hardware and environment?  
A: The Solution:  
1.Big 0 notation can objectively describe the efficiency of code without the use of concrete units.  
2.Focus on how the time and space requirements scale.  
3.Prepare for the worst case scenario.

Q: How do you apply the product rule to simplify Big O?  
A: The rule says that if Big 0 is the product of multiple terms, constant terms are eliminated (constant terms are like static numbers, numbers like 1, 4, 5, basically anything that is not a variable).  
After this, the sum rule should be applied.

Q: How do you apply the sum rule to simplify big O?  
A: The rule says that if big O is the sum of multiple terms, keep only the largest term and eliminate the rest.  
Before this, the product rule should be applied.

Q: What extra factor is taken into consideration when we want to calculate the space complexity of the recursive code?  
A: Our space complexity should consider the space taken by recursive calls on the call stack.  
When you analyze the space complexity of a recursive code, what you really have to think about is how many stack frames or how many recursive calls I have to make before I get to the base case.

---

TARGET DECK: Javascript::Interview::ALAIO - Learn algorithms in one week - alvin zablan

FILE TAGS: Javascript Interview

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```
