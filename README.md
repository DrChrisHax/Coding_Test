# C++ Programming Test

## Setup
1. Fork the repository
2. Clone the repository
3. Implement your LRU Cache solution
4. Run all of the tests
```
make run
```
5. Commit and push your changes
6. Send the link to your repository to drchrishax on discord when you are done.


# Coding Problem

## Background
Our systems regularly retrieve the same records, user profiles, and docuemt metadata in short bursts. Hitting the database on every request is expensive, so we rely on caches to serve repeated lookups fast. One of the most practical caching stategies is the Least Recently Used (LRU) cache. Whenever the cache is full and a new item needs to be inserted, the item that was accessed least recently is evicted to make room.

Your task is to implement an LRUCache class from scratch in C++. 
Starter code has been provided in LRUCache.cpp.


## Implementation
