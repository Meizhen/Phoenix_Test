WorkloadSchemaTest
==================

Workload and Schema Tests

Test: takes both the property and workload from the properties.xml file, prepare the 
JDBC prepared statement accordingly, build connection to server and execute the prepared queries

WorkloadTest: This test program is used to read the upgraded schema information from xml files like ColumnFamilySchema.xml, which can include bindings

WorkloadParse: This test program read the upgraded workload xml files like promoteKeyWorkload2.xml, building the prepared statement according to the statement and bindings and executes the queries
