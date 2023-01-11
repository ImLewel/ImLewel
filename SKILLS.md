# Personal profile of software engineering skills

⬜ Optional, 🟦 Required for all, 🟩 Learned, 🟥 Declined

## Fundamental concepts

| Syntax               | Statements             | Functions             | Data structures           | Process & style      |
|----------------------|------------------------|-----------------------|---------------------------|----------------------|
| 🟩 value             | 🟩 if                 | 🟩 recursion          | 🟩 Array                 | 🟩 refactoring       |
| 🟩 identifier        | 🟩 loops              | 🟩 function           | 🟩 instance              | 🟩 code review       |
| 🟩 variable          | 🟩 assignment         | 🟩 return             | 🟩 object                | 🟩 antipatterns      |
| 🟩 constant          | 🟩 break, continue    | 🟦 signature          | 🟩 Dictionary            | 🟩 paradigm          |
| 🟩 scalar            | 🟩 class              | 🟩 argument           | 🟩 Hashtable             | 🟩 algorithm         |
| 🟩 literal           | 🟩 while              | 🟩 parameter          | 🟩 LinkedList            | 🟩 magic numbers     |
| 🟩 expression        | 🟩 do..while          | 🟩 pure function      | 🟩 Queue                 | 🟩 hardcode          |
| 🟩 heap              | 🟩 for                | 🟩 lambda             | 🟩 Stack                 | 🟩 complexity        |
| 🟩 type              | 🟩 foreach            | 🟩 side effects       | 🟩 deque                 | 🟩 decomposition     |
| 🟩 primitive types   | 🟩 switch             | 🟩 closure            | 🟩 serialization         | 🟩 spaghetti         |
| 🟩 reference         | 🟩 new Error          | 🟩 partial            | 🟩 SortedList            | 🟩 silver bullet     |
| 🟩 flag              | 🟩 throw              | ⬜️ curry              | 🟩 iterator              | 🟩 not invented here |
| 🟩 lexical scope     | 🟩 try..catch         | 🟩 chaining           | 🟩 List                  | 🟩 dead code         |
| 🟩 code block        | 🟩 equality operators | 🟩 higher order       | 🟩 null                  | 🟩 unreachable code  |
| 🟩 namespace         | 🟩 logical operators  | 🟩 callback           | 🟩 ArrayList             | 🟩 duplicate code    |
| 🟩 this              | 🟩 bitwise operators  | 🟩 EventListener      | 🟩 ObservableCollection  | 🟩 exception         |
| 🟩 arrow function    |                       | ⬜️ pipe               | 🟩 HashSet                | 🟩 return early      |
| 🟨 generator         |                       | ⬜ compose            | 🟩 SortedSet              | 🟩 linter            |
| 🟩 async function    |                       | ⬜️ memoize            | 🟩 string parsing         | ⬜️ prettier          |
| 🟩 out, ref, in      |                       | 🟦 factory            | 🟩 timers                 | 🟦 unittest          |
| 🟩 typeof or GetType |                       | 🟩 pool               | 🟩 Event                  | 🟩 git               |
| 🟩 IsIstanceOfType   |                       | 🟩 wrapper            | 🟩 RegExp                 | 🟩 github            |
| 🟩 is                |                       | 🟩 default parameters | 🟨 global                 | 🟩 NuGet             |
|                      |                       | 🟩 LINQ                | 🟩 undefined              |                      |
|                      |                       |                        | 🟩 Object                 |                      |

## Multi-paradigm programming

| Theory                         | OOP basics            | Abstractions          | Patterns                 |
|--------------------------------|-----------------------|-----------------------|--------------------------|
| 🟩 Procedural programming      | 🟩 constructor        | 🟩 struct, record    | 🟩 Singleton            |
| 🟩 Imperative programming      | 🟩 new                | ⬜ Mutable state     |                          |
| 🟩 Structured programming      | 🟩 Static method      | ⬜ Immutable state   |                          |
| 🟩 Non-structured programming  | 🟩 Method             | 🟩 Enum              |                          |
| 🟩 Functional programming      | 🟩 Async method       | 🟦 Linked list       |                          |
| 🟩 Prototype-based programming | 🟩 Getters, Setters   | 🟦 Doubly list       |                          |
| 🟩 Object-oriented programming | 🟩 Public fields      | 🟦 Unrolled list     |                          |
| ⬜ Object-based programming    | 🟩 Private fields     | 🟦 Circular list     |                          |
| 🟦 Generic programming         | 🟩 Field declarations | 🟦 Trees             |                          |
| 🟦 Concurrent computing        | 🟩 Inheritance        | 🟦 Graphs            |                          |
| 🟩 Asyncronous programming     | 🟩 Parent class       | 🟦 Functor           |                          |
| 🟦 Parallel programming        | 🟩 Polymorphism       | 🟦 Functional object |                          |
| 🟦 Reactive programming        | 🟩 Abstract class     | ⬜ Monad             |                          |
| ⬜ FRP (Functional-reactive)   | 🟩 Interface          | 🟦 Generator         |                          |
| 🟦 Automata-based programming  | 🟩 Encapsulation      | 🟦 Iterator          |                          |
| 🟦 Domain-specific languages   | 🟩 Override           | 🟦 Async Iterator    |                          |
| 🟦 Multi-paradigm programming  | 🟩 Virtual            |                      |                          |
| ⬜ Metaprogramming             | 🟩 base               |                      |                          |
| ⬜ Actor model                 | 🟩 instance           |                      |                          |

## Asynchronous programming

| Async contracts        | JavaScript & Node.js specific   | Theory               | Techniques               |
|------------------------|---------------------------------|----------------------|--------------------------|
| 🟦 Callback-last       | 🟦 Timers                      | 🟩 Event Loop        | ⬜ async.js library    |
| 🟦 Error-first         | 🟦 setImmediate                | 🟦 Async error       | ⬜ Async composition   |
| 🟦 Promise             | 🟦 nextTick                    | 🟩 try..catch        | ⬜ Rx.js               |
| 🟦 Async function      | ⬜ AbortController             | 🟦 Non-blocking      | 🟦 Sequential async    |
| 🟦 await               | 🟦 Promise unhandled rejection | 🟩 Async I/O         | 🟦 Parallel async      |
| 🟦 Generator           | 🟦 Promise double resolve      | 🟦 Pattern Reactor   | 🟦 Promise.all         |
| 🟦 Async Generator     | 🟦 child_process               | ⬜ CAS operations    | 🟦 Promise.allSettled  |
| 🟦 Async Iterator      | 🟦 worker_threads              | ⬜ epoll             | 🟦 Promise.race        |
| 🟦 Thenable            | 🟦 Atomics                     | ⬜ kqueue            | 🟦 Promise.any         |
| 🟦 EventEmitter        | 🟦 Blockeing operations        | ⬜ Completion ports  |                        |
| ⬜ Cancelable callback | 🟦 Non-blocking loop for Array | ⬜ Event ports       |                        |
| ⬜ Cancelable Promise  | ⬜ High resolution clock       | 🟦 libuv             |                        |
| 🟩 Asynchronous Queue  | 🟦 Callback hell               | 🟦 Race conditions   |                        |
| ⬜ Future              | 🟦 Promise hell                | 🟦 Dead locks        |                        |
| ⬜ Deferred            |                                 | 🟦 Live locks        |                        |
| 🟦 Observer            |                                 | ⬜ Actor Model       |                        |
| ⬜ Async Collector     |                                 |                      |                        |
| 🟩 Coroutine           |                                 |                      |                        |
| ⬜ Goroutine           |                                 |                      |                        |


