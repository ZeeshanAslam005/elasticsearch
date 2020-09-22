# README

Elasticsearch (ES) is a powerful Full Text Search Engine based on Apache Lucene. 
An information retrieval software library. It provides distributed full-text search based on an HTTP interface. It’s written in Java and developed by Elastic.co. It’s similar to Apache Solr or Sphinx (maybe you have used one of them before).

It’s also used by a lot of big companies like Facebook, Netflix or Mozilla. You can find out more on their official webpage.
Things you may want to cover:

* Ruby version

* https://www.nopio.com/blog/elasticsearch-rails/


ES is document oriented; it stores its entire objects inside documents. It also indexes these documents to make them searchable. A document belongs to a type and a type belongs to an index. You can draw some parallels to how a traditional relational database is structured:

1
2
Relational DB  ⇒ Databases ⇒ Tables ⇒ Rows      ⇒ Columns
Elasticsearch  ⇒ Indices   ⇒ Types  ⇒ Documents ⇒ Fields

Each ES Index can be split into multiple pieces called shards.