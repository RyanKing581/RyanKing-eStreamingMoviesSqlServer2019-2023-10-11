# RyanKing-eStreamingMoviesSqlServer2019-2023-10-11
erwinDM eMovies model
In this model, I took everything that was included in the sample model provided by the erwinDM team and added some additional tables to their diagrams.
Firstly, the sample model is a physical/logical data model so that means that the diagrams for the logical and physical data models were already included.
Second, I renamed the ER diagrams into their respective data model types so that it's easier to tell which diagrams are represented as what type of model we are designing.
Third, I started creating my own conceptual data model (CDM) since the sample model did not include one.
Lastly, to modernize our design, I added more tables named "Record Logs" and "Membership" to keep track of employee records and customer subscriptions. These two tables have a many-to-many relationship with the employee table, customer table, and invoice table respectively.
