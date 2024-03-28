# pg-digsig
Digital signature extension for PostgreSQL

The idea of this proposed extension is to add the ability to integrate ETSI/ZertES qualified digital
signatures of data in a PostgreSQL database directly into a PostgreSQL database server. 

The extension should be able to create a signature  of data in a row, and store the signature
as part of that row in the database.

Depending on where the database is hosted, it should be able to do ETSI and/or ZertES (or further specifications
as needed) signatures on the data as required. 

In the case of data such as PDF documents that have an embedded signtaure, this signature should be stored
in the database and in the document

The option of a qualified timestamp in the row data should also be provided.
