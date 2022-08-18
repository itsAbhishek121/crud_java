# crud_java

=> This is Readme file.

-> Here, I created Java based library for executing SQL queries for create, read, update, delete (CRUD) operations against an RDBMS. 

-> For storing queries, XML file is used.

-> I used DOM Parser to read the XML file and to extract queries.

-> After that for executing that queries for specifiec method, I used JDBC. For that I used mySQL connector.

-> Implemented 5 methods: select_one, many_one, insert, update and delete.

-> Additional methods: Parser, which is a used to read queries and getconnection, which is used for establishing connection with database server.

-> These fuctions will take query id (unique) as a argument for searching queries in XML file. 

-> Insert, Update and Delete method will return no. of rows affected.

-> Select_one and Select_many will return data objects and these also take query parameters as argument by which queries willl be populated at run time.

-> I also implemented Unit Test Cases using Junit for checking the methods implemented.

-> I used sakila database for testing purposes. 

-> For buliding this assigment I used GRADLE, build automation tool.
README.txt
Displaying README.txt.
