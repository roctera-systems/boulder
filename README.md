# boulder

A lightweight, high-performance in-memory data store written in modern C++. Boulder implements the Redis protocol (RESP) and core data structures, designed for learning systems programming and demonstrating production-quality infrastructure code.

## Features

- High-performance event-driven architecture using epoll/kqueue
- Redis-compatible RESP protocol implementation
- Core data structures: Strings, Lists, Sets, Hashes, Sorted Sets
- Non-blocking I/O with efficient connection handling
- Built-in benchmarking and performance metrics
- Comprehensive test suite
- Thread-safe operations

## Why Boulder?

Boulder was built to understand the internals of high-performance key-value stores from the ground up. Every line of code demonstrates:
- Systems programming fundamentals in C++
- Network protocol implementation
- Memory management and optimization
- Concurrent data structure design

## Quick Start
```bash
# Build
make

# Run server
./boulder-server --port 6379

# Connect with redis-cli
redis-cli -p 6379
```

## Roadmap

- [ ] Basic GET/SET operations
- [ ] TCP server with non-blocking I/O
- [ ] Persistence (RDB snapshots)
- [ ] Pub/Sub support
- [ ] Cluster mode
- [ ] Lua scripting

Built with ❤️ by Roctera Systems
