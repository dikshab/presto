=============
Release 0.101
=============

General Changes
---------------

* Add support for :doc:`/sql/create-table` (in addition to :doc:`/sql/create-table-as`).

Hive Changes
------------

* Add support for connecting to S3 using EC2 instance credentials.
  This feature is enabled by default. To disable it, set
  ``hive.s3.use-instance-credentials=false`` in your Hive catalog properties file.
