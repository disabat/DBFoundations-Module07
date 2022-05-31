# Assignment 07

## Introduction

User Defined Functions are custom functions. These may be Scalar, Inline, or Multi-Statement Functions. This document explains each

## User Defined Functions 

A User Defined Function, abbreviated UDF, is a custom function. There are already functions built into SQL Server, and these are used to transform the data in some way. Some examples are computing the Average or ranking rows. UDF’s are defined by the user and saved for later recall. UDF’s are used when you want to transform the data in a custom way. For example, when using a movies database one might want to identify movies over 2 hours long and save this as a table for later use. One can also create scalar (single value vs. a table) UDF’s. The advantage of using UDF’s is it saves time – the code can be written and then the resulting function can be called when needed.

## Scalar, Inline, and Multi-Statement Functions

Scalar functions return a single value as a result of the query. For example, one might want to create a function that multiplies two distinct values. 
>“An inline function is similar to a view. This means that an inline function can only contain a single SELECT statement, and the columns in the SELECT statement implicitly define the columns of the returned table set of the function” (SQLSunday.com, https://sqlsunday.com/2013/05/05/table-value-vs-inline-table-functions/, 2022 [external link]). 

Finally, a multi-statement function includes multiple SELECT statements to return more complex data.

## Summary

Functions are important ways to transform the data and return either a single value or a table of data. Functions can be later called up, saving actual and processing time. They are handy for recalling data that will be frequently used.
