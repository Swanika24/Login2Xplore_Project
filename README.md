# Hi, Late Aarti! 🙂 
## Welcome to my Micro Project of Login2Explore...

Project Name: Student Enrollment From using JsonPowerDB
Student Enrollment Form that will store data in STUDENT-TABLE relation of SCHOOL-DB database.

Input Fields: {Roll-No, Full-Name, Class, Birth-Date, Address, Enrollment-Date}

Primary key: Roll No.

# Benefits of Using JsonPowerDB
In the world of API craft, no area is more hotly discussed than design. From REST, gRPC, to GraphQL, there are many approaches to designing and standardizing web API interactions. Today we turn our focus to another approach, JSON API, a specification for building APIs detailed at JSONAPI.org.

JSON API, described at JSONAPI.org, is great for making your JSON response formatting more consistent. With the goal being to increase productivity and efficiency, JSON API has been touted for its efficient caching features that can eliminate superfluous server requests.

In this piece, we’ll define what JSON API is, and see how it might be used to build efficient APIs. We’ll introduce some of the main benefits of JSON API, and also peek into case studies at FitBit to see how this specification has been used in practice. Hopefully, this overview will introduce newcomers to JSON API and help you gauge if it’s a right fit for your API scenario.

JsonPowerDB is a high-performance, schema-less, and developer-friendly database management system. It offers several powerful features that make it a versatile choice for modern application development. One of its standout features is real-time data synchronization, which enables developers to build responsive and dynamic applications.

## Release Notes

* Completed Phase-4 of Pluggable API framework for configuration properties that controls the usage of API for global and individual users.
* Added NEW pluggable API for importing data from CSV files.
* Modified existing Drive API to support the Phase-4 of Pluggable API release.
* Development for Phase-1 for Replication of user's database - Replica Manager Dashboard, Sync user database from MasterNode to ReplicaNode(s) completed. 
* Added: New methods in jpdb-commons.js (0.0.4 and 0.0.5) for creating the 
  COPY COLUMN request i.e. createCopyColumnRequest(token, jsonObj, dbName, relName), 
  RENAME COLUMN request i.e. createRenameColumnRequest(token, jsonObj, dbName, relName), 
  REMOVE COLUMN request i.e. createRemoveColumnRequest(token, jsonObj, dbName, relName), 
  CHANGE COLUMN request i.e. createChangeColumnTypeRequest(token, jsonObj, dbName, relName), 
  UPDATE RECORD request i.e. createUPDATERecordRequest2(token, jsonObj, dbName, relName).
* Improved: Documentation
