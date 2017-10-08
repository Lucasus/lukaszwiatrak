---
layout: post
title:  "Polymorphism"
date:   2017-09-09 23:07:00 +0200
categories: fundamentals
---

**Definition**

In this blog post I'll explain what _polymorphism_ is. Let's start with a definition:

> Polymorphism is an ability to have a variable or value that can have many different types. 

Languages that provide this ability are called _polymorphic languages_. Function which operands (values of its parameters) can have many different types is called _polymorphic function_. 

_Type_ in definitions above is defined as a set of values. Saying that _value x has a type X_ means that value x belongs to the type X.

Types in programming languages also often have corresponding interfaces that describe what operations particular type provides. If a variable or value is polymorphic (can have different types), then those types should share a common structure (interface), so the code that operates on it is identical regardless of what is the actual type of this variable or value. 

**Taxonomy**

We can distinguish at least four types of polymorphism, divided between two categories: _universal_ polymorphism and ad-hoc _polymorphism_

![image tooltip here](/assets/polymorphism_taxonomy.png){: .center-image }

**References**

* The definition of _polymorphism_ I liked the most comes from [Wikipedia](https://en.wikipedia.org/wiki/Polymorphism_(computer_science))
* Good reference on this topic is [On Understanding Types,
Data Abstraction, and Polymorphism](http://lucacardelli.name/Papers/OnUnderstanding.A4.pdf) paper. Definitions here are mostly based on ones from it.


