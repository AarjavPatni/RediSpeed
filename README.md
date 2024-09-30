# RediSpeed

RediSpeed is a custom implementation of Redis, built from scratch in C++. This project aims to create a high-performance, in-memory data structure store that can be used as a database, cache, and message broker.

**⚠️ Note: RediSpeed is currently a work in progress.**

## Overview

RediSpeed is an educational project that seeks to recreate the core functionality of Redis. By building my own Redis-like system, I aim to gain a deeper understanding of in-memory databases, concurrent programming, and network protocols.

## Getting Started

(Instructions for building and running the project will be added as development progresses)

## Features

1. **Basic Functionality**
   - [x] ~~Implement a basic TCP server~~
   - [ ] Support response for multiple PINGs
   - [ ] Implement debugging capabilities (ECHO command)
   - [ ] Handling concurrent clients
   - [ ] Create a simple key-value store for strings (GET, SET commands)
   - [ ] Support for key expiry

2. **Replication**
   - [ ] Server info retrieval (INFO command)
   - [ ] Sending and receiving handshake
   - [ ] ACK and WAIT command support

3. **RDB Persistence**
   - [ ] Reading single keys
   - [ ] Reading multiple keys
   - [ ] Reading values with expiry

4. **Transactions**
   - [ ] Add functionality to increment values (INCR)
   - [ ] MULTI and EXEC commands to start transactions
   - [ ] Execution of empty transactions
   - [ ] Execution of transactions containing mutliple commands
   - [ ] Failure handling
   - [ ] Support multiple concurrent transactions

5. **Streams**
   - [ ] Creation of Redis streams (XADD command)
   - [ ] Validation and auto-generation of entry IDs
   - [ ] Static stream query (XRANGE)
   - [ ] Real-time stream query (XREAD)
   - [ ] Add blocking support for XREAD

## Contributing

As this is a personal educational project, contributions are not currently being accepted. However, feedback and suggestions are always welcome!


## Disclaimer

RediSpeed is not affiliated with or endorsed by Redis Labs. This is an independent, educational project aimed at learning and exploring the concepts behind Redis-like systems.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
