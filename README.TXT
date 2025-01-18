DDL = data defination language
                              |--> decimal (5,2)
                              |--> integer 
                              |--> char (fixed length
                              |--> varchar (not fixed , required space )
                              |--> Date 
to create table
    create table _name of table_ (Column No integer(10), Ename char(20));
to see detail of table
    desc tableName
                            ^---- (colurm == attribute, row == tuple_

eg :                           _
    CREATE TABLE Employee (     |     
      Sr_No INTEGER,            |___ (to create table)
      Ename VARCHAR(20)         | 
    );                         _|

    desc Employee;             |---- to show table information
--------------------------------------------------------------------
                      INSERT DATA INTO TABLE:
INSERT INTO Employee (Sr_No, Ename) values (1,'Yash');     |-------- for Single Line.
                                                          _
INSERT all                                                 |
    INTO Employee (Sr_No, Ename) VALUES(1, 'Yash')         |
    INTO Employee (Sr_No, Ename) VALUES(2, 'Khushant')     |--------for multtiple insert.
    INTO Employee (Sr_No, Ename) VALUES(3, 'Jay')          |
    INTO Employee (Sr_No, Ename) VALUES(4, 'Sanju')        |
select * from Employee;                                   _|
                                                            
select * from Employee;                                    ---------to view table.

____________________________________________________________________
####################################################################


            
