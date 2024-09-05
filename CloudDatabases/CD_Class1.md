## Class 1

#### What will we learn

- Azure Table Storage
- Azure Storage Queues (and Service bus)
- Azure Blob Storage
- Azure CosmosDB
- Entity Framework (Relation SQL server and with CosmosDB)

##### Azure Table Storage

Based on SQL/very similar to SQL. Uses 'row' and 'partition' keys instead of primary and foreign keys.

- Uses NoSQL's 'Key - Value' storage mechanism
- Rows are called entities
- Combination of 'row' and 'partition' keys must be unique
- Partition key is the most significantly different data, such as a
- Doesn't enforce/use schema's
- Writing uses JSON
- Writing is fast with known PartitionKey and RowKey
- Can be expensive to read
- Max size is 500TB.
- Highly scalable
- Mostly used for: Serverless, logging, configuration store and (sometimes) web apps
- Very cheap! Especially when the amount of users are low

###### Research

- What are Etags?
- How exactly do Partition and Row keys work?

#### Tools

- Create diagram -> draw.io
  - Get the Azure components
-

#### Research:

- Different message queue options
- When to use which cloud database option
- How to setup API gateways
- Polly -> What does it do exactly and how to set it up (setup not relevant yet)
- How to learn about the different Cloud (architecture) design patterns -> Book?
- What is gRPC and how does it work
-
