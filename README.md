# system-design Notes

## Key characteristics of Distributed systems

1. Scalability
2. Reliability
3. Availability
4. Efficiency
5. Serviceability or Manageability

## Load Balancing Algorithms

- Reduces individual server load
- Prevents single point of failure
- LB should only forward requests to healthy servers

1. Least Connection Method
2. Least Response Time
3. Least Bandwidth
4. Round Robin
5. Weighted RR
6. IP Hash

## Caching

- Short term memory
- Limited space
- Can exist at multiple levels

### App server Cache

### CDN

### Cache Invalidation

### Cache Eviction Policies

## Data Partitioning

- process of breaking up database

### Partitioning Methods

### Partitioning Criteria

### Common problems of Data partitioning

## Indexes

## Proxies

## Redundancy & Replication

## SQL vs NoSQL

## CAP (Consistency, Availability & Partition Tolerance)

## Consistent Hashing

## Long Polls vs Web sockets vs Server Side Events (SSE)

## Step - By - Step

1. Requirement Clarifications
2. System Interface Definitions
3. Back of the envelope estimation
4. Defining the Model
5. High Level Design
6. Detailed Design
7. Identifying and resolving bottlenecks
