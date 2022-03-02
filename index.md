**Name:** Alicia Blake

**Date:** March 01, 2022

**Course:** IT FDN 130 A Wi 22: Foundations of Databases & SQL Programming

**Assignment:** Assignment 07

# Assignment 07 - Functions
When to use a SQL UDF and the differences between Scalar, Inline and Multi-Statement Functions.

## Introduction

In this essay, I discuss when you would use a SQL User Defined Function, as well as the differences between Scalar, Inline and Multi-Statement Functions. 

## Use of SQL UDF (User Defined Functions)
When you need to create you own custom function, you would use a User Defined Function. A UDF works well as another abstraction layer option for a user to apply parameters in order to return SELECT statements in a protected way. They also allow more complex functions to be combined when a set of rows needs to be returned, but may require multiple steps.  

## Scalar, Inline, and Multi-Statement Functions
Scalar functions allow you to bring back a single value, based on a set of (optional) parameters. In a Scalar function, you need to define parameters and use begin and end. An Inline function is when you want to create a function that creates a table of data based on a set of (optional) parameters and returns a single set of rows. In an Inline function, only a SELECT statement can be used after the table is defined to build the function with identified parameters. Lastly, a multi-statement “returns a table of data, but only after additional processing” (Wise Owl Training) and returns a set of rows that allows the use of statements other than just SELECT, such as INSERT. It requires the use of BEGIN and END to capture all statements written into the function. It’s also necessary to define a table variable within the syntax of this function. 

## Summary
In summary, we have reviewed SQL User Defined Functions and the basic definitions of the common types.
