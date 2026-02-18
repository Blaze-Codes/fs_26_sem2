---
title: Glossary
---
A small collection of important technical terms


| technical term              | meaning / usage                                                                                                                                        |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Parallelism                 | multiple things happening at the same time                                                                                                             |
| Concurrency                 | challenge of managing shared resources                                                                                                                 |
| Mutual Exclusion            | fundamental property that ensures only one thread or process can access a resource                                                                     |
| Lockout                     | resource is free, but process still has to wait                                                                                                        |
| Starvation                  | situation, where a process is perpetually denied access to the resource it needs to make process                                                       |
| Deadlock                    | two processes have to wait for each other to complete, nothing happens                                                                                 |
| Livelock                    | similar to deadlock, but something gets executed infinitely (e.g. raising and lowering flag)                                                           |
| Communication Protocol      | set of rules or mechanisms ensuring that processes and threads coordinate and exchange information correctly and efficiently                           |
| Bad Interleaving            | An interleaving that results in an error/exception or undesirable outcome                                                                              |
| Synchronization             | a form of orchestration via threads, usually to prevent bad interleavings                                                                              |
| synchronized (java keyword) | used to control access to shared resources among multiple threads, ensuring that only one thread can execute a synchronized method                     |
| volatile (java keyword)     | used to indicate that a variable's value will be modified by different threads, ensuring that all threads read from the main memory, not the CPU cache |




Note: just found that https://cgl.ethz.ch/teaching/parallelprog25/pages/terminology.html
