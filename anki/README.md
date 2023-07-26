# ALAIO - Learn algorithms in one week - alvin zablan

## Questions

### Part I - The Complete Guide to Big O Notation & Complexity Analysis for Algorithms

#### Chapter 1 - Part 1

P: Why do we use Big 0?  
R: It's a framework we can use to judge which solutions are "better" than others.

P: What makes a solution "better"?  
R: We prefer solutions that use the least resources:  
1.time (duration)  
2.space (memory)

P: How do we control for differences in computer hardware and environment?  
R: The Solution:  
1.Big 0 notation can objectively describe the efficiency of code without the use of concrete units.  
2.Focus on how the time and space requirements scale.  
3.Prepare for the worst case scenario.

P: How do you apply the product rule to simplify Big O?  
R: The rule says that **if Big 0 is the product of multiple terms, constant terms are eliminated (constant terms are like static numbers, numbers like 1, 4, 5, basically anything that is not a variable)**.  
After this, the sum rule should be applied.

P: How do you apply the sum rule to simplify big O?  
R: The rule says that **if big O is the sum of multiple terms, keep only the largest term and eliminate the rest.**  
Before this, the product rule should be applied.

P: What extra factor is taken into consideration when we want to calculate the space complexity of the recursive code?  
R: Our space complexity should consider the space taken by recursive calls on the call stack.  
When you analyze the space complexity of a recursive code, what you really have to think about is how many stack frames or how many recursive calls I have to make before I get to the base case.

#### Chapter 2 - Part 2

P: What does it mean that the complexity class is Constant - O(1)?
R: Constant time means that the number of steps/operations does not depend on the input size. Also known as O(1). Predictability is always good

P: What does it mean that the complexity class is Logarithmic - 0(log(n))?  
R: It means that the number of steps can be expressed as a logarithm of the size of the input.  
**Logarithms Explained**  
1.A log is the opposite of an exponent  
2.An exponent is a repeated multiplication, a log is a repeated division  
3.If 2^5 = 32 , then log2(32) = 5
it stops when it reaches 1

P: What does it mean that the complexity class is Linear - O(n)?  
R: Means that the number of steps depends on the input size.

P: What does it mean that the complexity class is Loglinear - 0(n\*log(n))?
R: O(n log n) implies that log n operations will occur n times.  
1.Has linear behavior nested in log steps  
2.Is bigger than O(n) but smaller than O(n^2)  
e.g. O(n log n) time is common in recursive sorting algorithms, binary tree sorting algorithms and most other types of sorts.

P: What does it mean that the complexity class is Polynomial (includes quadratic, cubic, etc.) - O(n^c)?  
R: It means that our variable n will have a constant number as exponent.
1.n is the size of the input  
2.c is some constant  
3.Includes 0(n2) quadratic, 0(n3) cubic, etc.

P: What does it mean that the complexity class is Exponential - O(c^n)?  
R: It means that:  
1.n is the size of the input  
2.c is some constant  
3.Includes O(2^n), 0(3^n), etc.

P: What does it mean that the complexity class is Factorial - O(n!)?  
R: The time complexity of calculating n! is proportional to the size of the input, which is n. Each number from 1 to n needs to be multiplied together, resulting in a time complexity that grows rapidly with increasing values of n.
1.n! = (n) (n-1) (n-2) (n-3)...(2) (1)  
2.4! = 4 \* 3 \* 2 \* 1 = 24

P: How should you handle functions with multiple arguments?  
R: You should separate the arguments/variables with different letters to identify them and specify what they represent.
For example:
1.O(n) = O (m+n), Where m, n are the array lenghts  
2.0(max(m, n) ), where m, n are the string lengths  
3.0(n), where n is the length of the longer string

P: How do you determine the stack space in a recursion?  
R: What you need to do is visualize what the recursion tree looks like and then consider the maximum stack depth you are going to use. Normally the space used will be the height of the tree.

---

DECK INFO

TARGET DECK: Javascript::Interview::ALAIO - Learn algorithms in one week - alvin zablan

FILE TAGS: Javascript Interview

Tags:

Reference:

Related:

```dataview
LIST
where file.name = this.file.name
```
