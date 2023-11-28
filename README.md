# File-Management-System

A robust file management system to organize, store, and retrieve files efficiently.


## Backend
When a user uploads a picture, it is stored in an S3 bucket, and the object URL is then stored in the database. The list of files is loaded from the S3 bucket. Users can download and delete files from the list, and all these processes are facilitated through the S3 bucket and the database.

[Backend Repository](https://github.com/Smoke221/File-Management-System)

[Backend Deployement](https://fs-filestorage.cyclic.app/)
