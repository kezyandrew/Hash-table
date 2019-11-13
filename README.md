# Hash-table
 #Hashing data structure 
 
Hashing data structure is the process of mapping a large amount of data to a smaller value using a hashing function and the    value is stored in a hash table.

A hash function takes a group of characters called a key and maps it to a value of a certain length called a hash value it is usally got by the formular:

                x= key % length of the hash table
                x is the hash value
                
A data table then can be described as a data structure that basically maps keys to values or indixes

In the notebook we see that we start by creating an empty table in form of an array, this table has a length of 10 

 Then we formulate our hash function with the above formular and we see that when we put in some keys we generate hash values.
 
 These hash values represent the string values that we want to insert into the table.
 
 We define a function to insert data into the table as seen in the notebook.
 
 Our table now maps keys to indixes in the table but what if a new we enter a value that has the same hash value and the index is 
 already occupied in the table, we see that that value is replaced by the new value.
 
 This problem is called collision and it can be solved by chaining
 
 Chaining 
 
 
 
 
 
 
 
 


