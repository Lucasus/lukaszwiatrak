---
layout: post
title:  "Fundamental concepts: polymorphism"
date:   2017-09-09 23:07:00 +0200
categories: fundamentals
---

**Definition**

In this blog post I'll explain what _polymorphism_ is. Let's start with a definition:

> Polymorphism is the provision of the same interface to entities of different types. 

In other words, we can have entity that has many different types. The code that interacts with it doesn't need to know what is an actual type of the entity. It only needs to know (and operates on) common interface of those types.

_Entity_ in definition above means a variable, value or function. _Interface_ is a set of operations that entity provides (or a single signature if an entity is a function)

**References**

* The definition of _polymorphism_ I liked the most comes from [Wikipedia](https://en.wikipedia.org/wiki/Polymorphism_(computer_science))
* Good reference on this topic is [On Understanding Types,
Data Abstraction, and Polymorphism](http://lucacardelli.name/Papers/OnUnderstanding.A4.pdf) paper. Definitions here are mostly based on ones from it.


