# DevOps Task

## The goal
Copy a part of the source s3 bucket's content to the destination s3 bucket. The exact number of objects is up to you, let it be 90% of the all files located in the source bucket.

## Prerequisites 
- Develop a script either with PowerShell (Windows) or bash (Unix)
- Fill the source bucket with random objects with inheritance of keys 4-5 levels. 
- The script must support threads with ability to change number of threads via a variable or so on.
- Please implement an algorithm and methods of copy objects in threads as fast as it possible with minimum impact to the performance of the host. Keep in mind that the real source bucket can contain billions of objects.
- The script must writes logs as detailed as necessary to determine the results of successful copy or failure for each file.

NOTE: duration of the task is 8 hours.

## Access
Request following information before start:
- Access key ID 
- Secret access key
- S3 bucket1 name
- S3 bucket2 name