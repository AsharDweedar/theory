- **What is Database transaction?**

  A transaction, in the context of a database, is a logical unit that is independently executed for data retrieval or updates

  you want to treat as "a whole." It has to either happen in full or not at all.

  A classical example is transferring money from one bank account to another. To do that you have first to withdraw the amount from the source account, and then deposit it to the destination account. The operation has to succeed in full. If you stop halfway, the money will be lost, and that is Very Bad.

  In modern databases transactions also do some other things - like ensure that you can't access data that another person has written halfway. But the basic idea is the same - transactions are there to ensure, that no matter what happens, the data you work with will be in a sensible state. They guarantee that there will NOT be a situation where money is withdrawn from one account, but not deposited to another.

- **Database Indexing?**

  https://stackoverflow.com/questions/1108/how-does-database-indexing-work

  https://www.youtube.com/watch?v=zDzu6vka0rQ

- **What ORMs did you use? how are they useful?**

  "mongoose .. example" , **Object-relational mapping (ORM)** is a layer that converts our data between Database and object-oriented entities using object-oriented programming (OOP) language.

- **Mention some aggregation functions in mongo, and what they do?**

  Aggregation operations process data records and return computed results. Aggregation operations group values from multiple documents together, and can perform a variety of operations on the grouped data to return a single result.

- **what is Views in mongodb?**

  A queryable object whose contents are defined by an aggregation pipeline on other collections or views.

- **Sql query to get the fifth highest salary inside employees table**

  sort data --> limit it to 5 --> take the fifth value.
