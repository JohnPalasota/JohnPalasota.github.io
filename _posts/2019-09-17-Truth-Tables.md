---
layout: post
title: Truth Tables
---

## Tautology (True)
 a    b   result 
 
 ----------------
 
 t    f    true   
 f    f    true   
 t    t    true   
 f    t    true  

## Contradiction (False)
 a   b   result 
 
-----------------

 t  f  false   
 f  f  false   
 t  t  false   
 f  t  false   

## Proposition A
 a b result 
 
-----------------

 t  f  true   
 f  f  false  
 t  t  true   
 f  t  false  

## Proposition B
 a  b  result 
 
-----------------
 
 t  f  false  
 f  f  false  
 t  t  true   
 f  t  true   

## Negation of A (!a)
 a  b  result 

-----------------

t  f  false  
 f  f  true   
 t  t  false  
 f  t  true   

## Negation of B (!b)
a  b  result 

-----------------

t  f  true   
 f  f  true   
 t  t  false  
 f  t  false  

## Conjunction (a && b)
 a  b  result 

-----------------

t  f  false   
 f  f  false   
 t  t  true   
 f  t  false   

## Alternative Denial (!(a && b))
 a  b  result 

-----------------

t  f  true   
 f  f  true   
 t  t  false  
 f  t  true   

## Disjunction (a || b)
 a  b  result 

-----------------

t  f  true   
 f  f  false  
 t  t  true   
 f  t  true   

## Join Denial (!(a || b))
 a  b  result

-----------------

t  f  false   
 f  f  true   
 t  t  false  
 f  t  false  

## Material Nonimplication (a -/> b)
 a  b  result 

-----------------

t  f  true   
 f  f  false   
 t  t  false   
 f  t  false   

## Material Implication  (a --> b)
 a  b  result 

-----------------

t  f  false  
 f  f  true   
 t  t  true   
 f  t  true   

## Converse Nonimplication (a </- b)
 a  b  result 

-----------------

t  f  false   
 f  f  false   
 t  t  false   
 f  t  true   

## Converse Implication (a <-- b)
 a  b  result 

-----------------

t  f  true   
 f  f  true   
 t  t  true   
 f  t  false  

## Exclusive Disjunction (a ^ b)
 a  b  result 

-----------------

t  f  true   
 f  f  false   
 t  t  false   
 f  t  true   

## Biconditional (!(a ^ b))
 a  b  result 

-----------------

t  f  false   
 f  f  true   
 t  t  true   
 f  t  false   
