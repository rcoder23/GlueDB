# GlueDB - A Redis-like In-Memory Database in Java

This project is a prototype of an in-memory key-value store . The goal is to implement basic features of Redis such as key-value operations, data persistence, and transactions.

## Features

### 1. Key-Value Operations
- **SET**: Store a key-value pair.
- **GET**: Retrieve the value associated with a key.
- **DEL**: Delete a key-value pair.

### 2. Data Persistence
- **SAVE (Snapshot)**: Periodically save the entire in-memory state to disk.
- **AOF (Append-Only File)**: Log every write operation to disk to ensure data persistence and enable recovery.

### 3. Transactions
- **MULTI**: Start a transaction.
- **EXEC**: Execute all queued commands in a transaction.
- **DISCARD**: Discard all queued commands in a transaction.
