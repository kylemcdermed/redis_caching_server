# Redis Caching Server

This repository provides implementations of a Redis-based caching server in both Python and C++. The server efficiently checks if a number is prime, caches the results in Redis, and serves client requests.

## Features

- Caches prime/composite results in Redis to reduce computation time for repeated queries.
- Multi-threaded server: Handles multiple client connections concurrently.
- Implements efficient prime-checking logic using caching and mathematical optimizations.
