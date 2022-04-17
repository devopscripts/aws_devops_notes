# aws_devops_notes

notes of preparing devops exam

## Monitoring and Logging

### Kinesis

#### limit

#### KCL DynamoDB

#### Kinesis Data Firehose

1. fully managed service
2. Near RT
3. Target S3, Redshift, ES, Splunk
4. Pay for data going through
5. auto scaling

#### Streams vs Friehose

|item|Streams|Firehose|
|--|--|--|
|1|custom code (producer/consumer)|fully managed
|2|Realtime(low latency)|Near RT
|3|manage scaling(shard splitting/merging)|Automated scaling
|4|Has Data storage|No data storage
|5|Use with Lambda to insert data to ES|serverless data transform with lambda

### CloudWatch

#### Metrics

##### EC2 Default metrics

1. CPU
2. Disk
3. Network
4. status check
5. CPU credit

##### EBS default metrics

1. Bandwidth read/write
2. ..

**No space utilisation metrics!!**

##### LB

1. RT
2. HTTP error
3. ELB errors
4. connection errors
5. active conn 
6. consumed capacity units

##### RDS

1. 