I started this project at Zvents when somebody asked me about the database schema.  After some head scratching, I realized it would be nice to have a program to automatically generate a descriptive list of tables and columns and present it in a nicely formated HTML page.

One can query the database directly to find out the names of tables, and columns, but also other useful information such as minimum/maximum values, counts of NULLs, counts of rows, etc.

Unfortunately, one thing that the schema doesn't have, is descriptions about the tables and columns.  Hence, the program uses a supplemental Description File that can provide additional documentation which gets merged into the HTML.

The Description File also allows one to link a Table ID field to a Table, making it much easier to navigate the Schema.

An example using the MySQL World sample database (http://dev.mysql.com/doc/world-setup/en/world-setup.html) is provided.

