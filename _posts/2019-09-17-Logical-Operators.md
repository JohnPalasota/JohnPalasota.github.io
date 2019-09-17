---
layout: post
title: Logical Operators
---

## Not (!)
### Returns true if the operand to the right is false. Returns false if the operand to the right is true.
Ex: `!true` returns false.



## Conditional And (&&)
### Returns true if both operands are true. However, if the first operand is false, the operand on the right will not be evaluated.
Ex: `false & true` returns false. However, it won't evaluate the true on the right of the  operator.



## And (&)
### Returns true if both operands are true. Both operands are evaluated no matter the result.
Ex: `false & true` returns false. However, it not only evaluated the operand on the left of the operator, it also evaluated the operand on the right.



## Conditional Or (||)
### Returns true if either of the operands on the left or right of the operator are true. However, if the operand on the left is true, it won't evaluate the operand on the right.
Ex: `true || false` returns true. However, it won't evaluate the operand on the right of the operator.



## Or (|)
### Returns true if either of the operands on the left or right of the operator are true. It will evaluate both sides of the operator, regardless on if the left is true or false.
Ex: `true | false` returns true and has evaluated both the left and right operands.



## Xor (^)
### Returns true if only one of the operands are true. It will return false if both or neither of the operands return true.
Ex: `true ^ false` returns true because only one of the operands are true.
