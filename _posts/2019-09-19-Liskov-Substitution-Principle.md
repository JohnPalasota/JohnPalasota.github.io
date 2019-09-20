---
layout: post
title: Liskov Substitution Principle
---

## Why would a Square class being a child of a Rectangle class break the rules of the Liskov Substitution Principle?
Imagine you are creating a Rectangle class. Within the class, the following methods would reasonably be included:
```
getHeight();
getWidth();
setHeight(int height);
setWidth(int width);
getArea();
```

Given these methods, it is reasonable the rectangle can:
1. have its height adjusted without effecting the width
1. have its height or width doubled, and it will double the area

Now, if you were to make a Square class that inherited from the Rectangle class, it would be expected to follow the properties of the Rectangle class above.
However, if you were to:
1. have its height adjusted, it would also need to have the width adjusted at the same time to be considered a square
1. have the height or width doubled, it would result in the total area being quadrupled because it would require both the width and height to be doubled.


Because the behavior of the square is so different than a rectangle's, a Square class should not be treated as a child of a Rectangle Class.
