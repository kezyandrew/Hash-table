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
 
 Chaining is a way of solving collision where each index of an array contains a link to a linked list containing key value pairs with the same hash value, it is a faster way to solve collision.
 
 Though collision can also be solved by linear probing using binary search through the table to look for a free index in the array to insert a key value with a similar hash value with that already existing in the table.
 
 When we look at the section of chaining in the notebook we see that we are solving collision of "Andrew" and "Kaweesa"
 
 In conclusion hashing is a very efficient technique for password authentication and in database to enable retrieval of items more quicly. 
 
 
 
 
 
 
 
 
 


