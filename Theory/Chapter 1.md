# THEORY- CHAPTER 1 



##### Data:

Data is defined as raw facts and figures collected from a source using some particularly defined method of collection of data. 

##### Data Processing Element:

The translation of collected data into meaningful information is called Data Processing. In the advanced fields of Data Analysis this is the required step before Data Interpretation

##### Desirable characteristics of an ideal data processing system:

1. Efficient memory utilisation
2. Concurrency
3. Security
4. Avoiding Redundancy
5. Simplicity

![image](https://user-images.githubusercontent.com/80255503/161503166-3cd27898-2c82-4c37-975d-9b76e3d3aecb.png)

---------------

##### FILE BASED SYSTEM

+ Data was stored and retrieved on the same host machine
+ The traditional directory and file structure was used to store and retrieve data
+ slowly, it was realised that it did not have major benefits and also, wasn't scalable

*** DISADVANTAGES OF FILE BASED SYSTEM:

+ Non- efficient memory utilisation and retrieval
+ In file system the metadata of the file system is needed before the implementation.
+ There are no concurrency protocols in File Systems
+ There is no security of data in file based systems opposed to the Role Based Security System in DBMS
+ There are no efficient Redundancy checks

-----------------

##### Data Dependency

It is a concept which is based on the fact that when multiple sets of data are integrated at a single places there are some attributes of data ( say A) that are based on some other attribute ( Say B). In this case we say that A and B are dependent on each other. This phenomenon is known as Data Dependency.

For Example if one table has the atrributes - Dept Number and Dept Name and the other has Dept Name and Dept Location, then the two tables have data dependent on each other. If the Dependence of data in this case is ignored, there may be a loss of Data Integrity and validity

----------------

#####  DATABASE

The collection of related Data is termed as a Database

It may be structured ( For example - University database) or Unstructured ( Webpages)


##### DATABASE MANAGEMENT SYSTEM

The Management of real time operations and Queries is done using a Data Base Management System

for example- Oracle server, MySQL


-----------------

The Traditional 2 tier client-server Architecture has been replaced with a 3- level Architecture where the client and the server both interact with a Business Layer or Application server or an interface. This means that the client and the server are virtually independent.

This provides- Scalability and Security but there is a maintainence overhead as compared to the old system

----------------

##### SCHEMA

The logical Representation of Data is called Schema

for example- Table is a schema

DDL ( Data Definition Language) is used to implement a schema


------------------

##### THREE SCHEMA ARCHITECTURE ( THREE LEVELS OF ABSTRACTION) 

This system was built with the goal to provide independence of the data and the user (Data Abstraction). The user is not concerned about the nitty-gritties of the storage of Data

![image](https://user-images.githubusercontent.com/80255503/161506728-a242da95-ecc7-4d51-a5d9-978b063cb21f.png)

+ The External Schema - The Different kinds of views based on the role of the user
+ Conceptual Schema - The relationship between various data
+ Internal Schema - The information about ' Where Data is Stored'
+ Physical Implementation - The Disks and storage devices where Data is actually stored



+ The Logical Data and the Physical Data are independent ( Logical Data Independence and Physical Data Independence). This means that any change in the Logical Data will not effect the External Schema. Similiarly the Physical Data must not impact the External view.\


-------------------------
