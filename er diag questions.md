ER Diagram Diagnosis:

1) What is the relationship between the "actor" and "film_actor" tables?

The actor_id is the primary key in the actor table and the foreign key in the film_actor table. This means for instance you couldn't delete the actor_id from the film_actor table since it's the child table.


2) What does the blue diamond next to the "last_update" column on the "inventory" table represent?

The blue diamond next to last_update in the inventory table indicates that it can not be NULL (an empty entry)

3) How many foreign keys does the "payments" table have?How can you tell?

The payments table has 3 foreign keys (customer_id, staff_id and rental_id). I can tell because they are all children from other tables where they are primary keys.
