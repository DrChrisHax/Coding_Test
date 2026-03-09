# C++ Programming Test - .NET intern position
## About the Role
We are hiring a software development intern. This is a flexible position where you can work 20-40 hours per week with flexible scheduling. The role is 100% in person for the first year at our office in Santa Ana, California.

### Tech Stack:
C#, VB.NET, SQL, .NET Framework

### Sponsership
Candidates must be authorized to work in the US. Visa sponsorship is not available for this role.

# Assignment
Your task is to implement an LRU (Least Recently Used) Cache in C++.

An LRU cache stores a fixed number of key-value pairs. When the cache is full and a new entry needs to be inserted, the entry that was accessed least recently is evicted to make room. This is one of the most common caching strategies used in production systems to avoid expensive repeated lookups against a database.

### Rules
- You can use any resouce online
- Do not modify any file marked DO NOT CHANGE THIS FILE
- Do not use std::list, but you can create your own implementation
- All code must go in the LRUCache.tpp file, do not create any other files

## Getting Started
1. Fork this repository
2. Clone your fork
3. Implement your solution in LRUCache.tpp
4. Build and run the tests:
```
# These tests will fail to compile if you do not stub out 
# or implement all the different functions
make run
```
5. Make sure all 20 test cases pass
6. Commit and push your changes

## Submission
Whe you finish:
1. Make sure all 20 test cases pass (make run)
2. Push your solution to your forked repository
3. Send the following to drchrishax on Discord:
    - A link to your repo (If I can't view it you will auto fail)
    - A copy of your resume

## Hints
- The starter Node struct is incomplete
- Think about how to get O(1) lookup and O(1) insertion/removal
- Pay attention to the Rule of Five (constructors, destructor, assignment operators)
- std::list is not allowed, but you can write your own list
- This test primarily tests your research skills, problem solving skills, and git skills. It is okay if C++ is not your primarily language