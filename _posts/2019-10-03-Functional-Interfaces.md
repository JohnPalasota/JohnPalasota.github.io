---
layout: post
title: Functional Interfaces
---

### Consumer
Consumer interface represents an operation that accepts a single input argument and returns no result.

Ex: `Consumer<String> c = (x) -> System.out.println(x.toLowerCase());`

### Supplier
Supplier represents a supplier of results. Has a get() method.

Ex: ```Supplier<Double> randomValue = () -> Math.random();
System.out.println(randomValue.get());```

### Function
Function represents a function that accepts one argument and produces a result.

```Function<Integer,String> converter = (i)-> Integer.toString(i);

System.out.println(converter.apply(3).length());
```

### Predicate
Predicate represents a predicate, which is boolean-valued function, of one argument.

`Predicate<String> i  = (s)-> s.length() > 5;`
