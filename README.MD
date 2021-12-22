# Analytics Assignment Youkraft

#### Instructions
1. Please write the answer to the questions 1 and 2 in a word document. 
2. Commit and push the App and the word document to a new repo in your personal git account to share the link to HR.
3. Read Me file should present with how to install and run the project. If it is missing then your submission will be considered as invalid.


### Question number 1

How do you define partion key in Kafka ?


### Question number 2

What is queue full exception ? when does it occur ?

### Create a pipe line for DB Events:

We store a lot of form data in our databases. A frequent task would be to read the events from the databases and push the latest changes to kafka or kinesis

Feel free to use any boilerplate and langauge of your use.

We care about code that is readable (even without comments), non-repeating (within reason) and structured well.

1. Create a databse of your choice SQL.
2. Table should have only 2 columns in SQL:
- id,
- Name
3. Create a pipeline from the db to kafka.
4. If a new record is inserted in the databases only that record must be inserted in the pipeline.
5. Show the log of the events.
