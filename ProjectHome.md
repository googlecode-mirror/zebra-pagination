## Zebra\_Pagination, a generic pagination class that automatically generates navigation links given the total number of items and the number of items per page ##

Please note that this is a **generic** pagination class, meaning that it does not display any records! It is up to developer to fetch the actual data and displaying it based on the information returned by this class. The advantage is that it can be used to paginate over records coming from any source (arrays, database, etc).

The appearance is customizable through CSS.

**Zebra\_Pagination**'s code is heavily commented and generates no warnings/errors/notices when PHP’s error reporting level is set to E\_ALL.