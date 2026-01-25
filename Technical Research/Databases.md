Relational databases seem the obvious choice as we know the structure of the data we would use. [Fireship Video](https://www.youtube.com/watch?v=W2Z7fbCLSTw) .
	Justification: Our data is structured and we want ACID compliance to prevent errors in bookings or data handling.
	Only downside is difficulty scaling. Several small tables (daily events table) could reduce the computational load as most of the time this is all that is needed at once.
A document database could work as schema may vary slightly from sport to sport. i.e. buggy hire? duration? outside? etc... This is object oriented so lends itself to python, javascript etc 
Fauna DB is a flexible, web option for a multi-modal database. This makes it available to deploy at scale, and the backend self-manages to deal with data how you want it the best. [Fauna DB Video]() Uses graphQL.

