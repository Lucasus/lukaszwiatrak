---
layout: post
title:  "Polymorphism"
date:   2017-09-09 23:07:00 +0200
excerpt: In this blog post I'll explain what polymorphism is. Let's start with a definition
categories: fundamentals
---

**Definition**

In this blog post I'll explain what _polymorphism_ is. Let's start with a definition:

> Polymorphism is an ability to have a variable or value that can have many different types. 

Languages that provide this ability are called _polymorphic languages_. Function which operands (values of its parameters) can have many different types is called _polymorphic function_. 

_Type_ in definitions above is defined as a set of values. Saying that _value x has a type X_ means that value x belongs to the type X.

Types in programming languages also often have corresponding interfaces that describe what operations particular type provides. If a variable or value is polymorphic (can have different types), then those types should share a common structure (interface), so the code that operates on it is identical regardless of what is the actual type of this variable or value. 

**References**

* [On Understanding Types,
Data Abstraction, and Polymorphism](http://lucacardelli.name/Papers/OnUnderstanding.A4.pdf)


