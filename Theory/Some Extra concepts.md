### Generalisation

A generalization hierarchy is a form of **abstraction** that specifies  that two or more entities that share common attributes can be  generalized into a higher-level entity type called a supertype or  generic entity. 


The lower level of entities becomes the subtype,  or categories, to the super type. 


Subtypes are dependent entities


--> 'IS A' Type of relationship amongst the 'Generalised' Entities

![image](https://user-images.githubusercontent.com/80255503/161591397-fc9f85d3-1a82-4acf-88aa-f6d4303b3ce7.png)


---------------------------


### Specialisation

Specialization is the process of taking subsets of a higher-level  entity set to form lower level entity sets. 

It is a process of  defining a set of subclasses of an entity type, which is called as  superclass of the specialization. 

The process of defining subclass  is based on the basis of some distinguishing characteristics of the  entities in the super class.


![image](https://user-images.githubusercontent.com/80255503/161591603-e21fce83-e0dd-482c-b6a0-1530c5a32911.png)


---------------------------


### Trivial Functional Dependency

If Y is FD on X ( X --> Y) and Y is a subset of X, then it is Trivial FD


Example - {Roll Number, Name , specialisation} ---> Roll Number

--------------------------


### Non-Trivial FUnnctional Dependency


If Y is FD on X ( X --> Y) and Y is not a subset of X, then it is Non-Trivial FD


Example - {Roll Number, Department, Semester_Number } ---> Student_Name

-------------------------

### How to Find the Primary Key when the FDs are given?

It should satisfy the following conditions

** It does not occur in any functional dependencies or, if it occurs, then it occurs only on the left side of the dependency


** The Attribute is not a part of the key if it occurs on the right side but not on the left side

** The Attribute may or may not be a part of the Key if it occurs on both sides of the FDs

Examples:

1. Let a relation R with attributes ABCD with FDs B → C, D → A. Find keys for relation R.

Here BD is the Key

2. Let a relation R with attributes ABCD with FDs A → B, BC → D and A → C. Find keys for relation R.

Here A is the Key

----------------------------
