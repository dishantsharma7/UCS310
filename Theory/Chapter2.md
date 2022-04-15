# RELATIONAL DATABASE MODEL

## RELATIONAL DATABASE

It represents the database as a colection of **relations**

Each relation, 'informally' is a table or a flat file of records

Each row of the table represents a collection of 'related' values

--------------------------

## TERMINOLOGY ASSOCIATED:

1. Tuple - A row in a relational database is called a 'tuple'
2. Attribute - A column header is called an attribute 
3. Relation - A table is called relation under relational database
4. Domain - The Data Type describing the type of values that can appear in each column is called Domain. A Domain D consists of the set of some atomic/ indivisible values



For A relation schema R:

1.  Denoted by R(A1, A2, . . ., An), is made up of a relation name R and a list of attributes A1, A2, . . ., An. 
2.  Each attribute Ai is the name of a role played by some domain D in the relation schema R.
3.  D is called the domain of Ai and is denoted by dom(Ai). 
4.  A relation schema is used to describe a relation
5.  R is called the name of this relation. 
6.  The degree of a relation is the number of attributes n of its relation schema

![image](https://user-images.githubusercontent.com/80255503/161529063-265a2ee1-fabf-4830-94d6-a1d5eb32c3d9.png)


------------------------

## CHARACTERISTICS OF A RELATION:

1. Tuple ordering is not part of a relation definition, because a relation attempts to represent facts at a logical or abstract level. For example the following two are logically equivalent as long as the mapping of the various attributes is correctly maintained.

![image](https://user-images.githubusercontent.com/80255503/161529467-c3e0582e-a01e-43fe-8b6d-84ef0fe27314.png)


2. each value in a tuple is atomic - composite and multi-valued attributes are not allowed
3. The relation schema can be viewed as an assertion/template/class and hence each tuple is an instance/object
4. The realtional model expresses both entities and the relationship between entities as relations

-------------------------

## KEYS


 A key is an attribute or set of attributes used to uniquely identify a tuple/relation/entity
 
 
 1. All the Possible Keys or combination of Keys which may be used to uniquely identify a relation are called **Candidate Keys**
 2. The most appropriate key from the set of the 'candidate keys' is called the **Primary Key**
 3. **Super Keys** is the combination of all possible attributes which can uniquley identify the tuples in a table. ***It is a super set of the candidate keys***. It may additionally contain some keys which are not used for unique identification
 4. All the keys which are not the primary keys are called as **Alternate/secondary Keys**


![image](https://user-images.githubusercontent.com/80255503/161532968-d0dd32d4-b3b8-47eb-97f2-4cec970d37f9.png)


5. A key which has multiple attributes to identify a row is called a **Composite Key**
6. A Key which is used to link a relation/table to another is called a **Foreign Key**. They are used to maintain the data integrity using referential integrity
7. A Key which is Artificially used to establish the uniqueness of a record is called a **Artificial or Surrogate Key**. They have no meaning in itself or no relation with database. Generally used in the absence of a Primary Key. For example: **Serial Number** in the following table

![image](https://user-images.githubusercontent.com/80255503/161533747-7d14b03d-4955-41ee-9469-a28381c78b90.png)


NULL VALUE -- It indicates absence of a value and NOT same as 0, It represents absence of data

--------------------------------

## RELATIONAL INTEGRITY

Relational Integrity constraints is referred to conditions which must be present for a valid relation. These integrity constraints are derived from the rules that the database represents.

There are three types of such Relational constraints

1. Domain Constraints
2. Entity Integrity/ Primary Key Constraints
3. Referential Integrity Constraints

![image](https://user-images.githubusercontent.com/80255503/161534777-4caeed5b-582c-4899-b77c-6db20190107f.png)


---------------------------------


CHECK CONSTRAINT- DISADVANTAGE - The domain in which it checks is static and is not applicable if it needs to be changed with varyuing demands









