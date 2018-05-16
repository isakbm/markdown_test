## Cassandra fundamental concepts & terms

* datacenter
* cluster
* node
* partition key
* cluster key
* column family
* [column family](#column-family)

* consistency
	* Availability is inverse to consistency. And partition tolerance is not optional, it is .

# Column family

> A column family (called "table" since CQL 3) resembles a table in an RDBMS.

>Cassandra and HBase have a concept of column families, which
they inherited from Bigtable. However, it is very misleading to
call them column-oriented: within each column family, they store
all columns from a row together, along with a row key, and they do
not use column compression. Thus, the Bigtable model is still
mostly row-oriented."

# Distributed Storage Systems

* rebalancing 
* partitioning
* 
