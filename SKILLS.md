# Personal profile of software engineering skills

⬜ Optional, 🟦 Required for all, 🟩 Learned, 🟥 Declined

## Fundamental concepts

| Syntax               | Statements            | Functions             | Data structures     | Process & style      |
|----------------------|-----------------------|-----------------------|---------------------|----------------------|
| 🟦 value             | 🟦 if                 | 🟦 recursion          | 🟦 array            | 🟦 refactoring       |
| 🟦 identifier        | 🟦 loops              | 🟦 function           | 🟦 instance         | 🟦 code review       |
| 🟦 variable          | 🟦 assignment         | 🟦 return             | 🟦 object           | 🟦 antipatterns      |
| 🟦 constant          | 🟦 switch             | 🟦 signature          | 🟦 collection       | 🟦 paradigm          |
| 🟦 scalar            | 🟦 class              | 🟦 argument           | 🟦 hash table       | 🟦 algorithm         |
| 🟦 literal           | 🟦 while              | 🟦 parameter          | 🟦 linked list      | 🟦 magic numbers     |
| 🟦 expression        | 🟦 do..while          | 🟦 pure function      | 🟦 queue            | 🟦 hardcode          |
| 🟦 heap              | 🟦 for                | 🟦 lambda             | 🟦 stack            | 🟦 complexity        |
| 🟦 type              | 🟦 throw              | 🟦 side effects       | 🟦 deque            | 🟦 decomposition     |
| 🟦 primitive types   | 🟦 try..catch         | 🟦 closure            | 🟦 serialization    | 🟦 git               |
| 🟦 reference         | 🟦 equality operators | 🟦 partial            | 🟦 mixin, extend    | 🟦 unittest          |
| 🟦 flag              | 🟦 logical operators  | 🟦 wrapper            | 🟦 Set              | 🟦 github            |
| 🟦 lexical scope     | 🟦 bitwise operators  | 🟦 chaining           | 🟦 nil              | 🟦 dead code         |
| 🟦 code block        | 🟦 break, continue    | 🟦 higher order       |                      | 🟦 unreachable code  |
|                       |                       | 🟦 callback           |                      | 🟦 duplicate code    |
|                       |                       | 🟦 listener           |                      | 🟦 exception         |
|                       |                       | 🟦 pool               |                      | 🟦 return early      |
|                       |                       | 🟦 factory            |                      | 🟦 linter            |

## Multi-paradigm programming

| Theory                         | OOP basics            | Abstractions         | Patterns                 |
|--------------------------------|-----------------------|----------------------|--------------------------|
| 🟦 Procedural programming      | 🟦 constructor        | ⬜ struct, record    | 🟦 Singleton             |
| 🟦 Imperative programming      | 🟦 new                | ⬜ Mutable state     |                          |
| 🟦 Structured programming      | 🟦 Static method      | ⬜ Immutable state   |                          |
| 🟦 Non-structured programming  | 🟦 Method             | ⬜ Enum              |                          |
| 🟦 Functional programming      | 🟦 Async method       | 🟦 Linked list       |                          |
| 🟦 Prototype-based programming | 🟦 Getters, Setters   | 🟦 Doubly list       |                          |
| 🟦 Object-oriented programming | 🟦 Public fields      | 🟦 Unrolled list     |                          |
| ⬜ Object-based programming    | 🟦 Private fields     | 🟦 Circular list     |                          |
| 🟦 Generic programming         | 🟦 Field declarations | 🟦 Trees             |                          |
| 🟦 Concurrent computing        | 🟦 Inheritance        | 🟦 Graphs            |                          |
| 🟦 Asyncronous programming     | 🟦 Parent class       | 🟦 Functor           |                          |
| 🟦 Parallel programming        | 🟦 Polymorphism       | 🟦 Functional object |                          |
| 🟦 Reactive programming        | 🟦 Abstract class     | ⬜ Monad             |                          |
| ⬜ FRP (Functional-reactive)   | 🟦 Interface          | 🟦 Generator         |                          |
| 🟦 Automata-based programming  | 🟦 Encapsulation      | 🟦 Iterator          |                          |
| 🟦 Domain-specific languages   | ⬜ Hidden class       | 🟦 Async Iterator    |                          |
| 🟦 Multi-paradigm programming  | ⬜ Object form        |                      |                          |
| ⬜ Metaprogramming             | 🟦 instance           |                      |                          |
| ⬜ Actor model                 | ⬜ Introspection      |                      |                          |
|                                | ⬜ Reflection         |                      |                          |

## Asynchronous programming

| Async contracts        | JavaScript & Node.js specific  | Theory              | Techniques               |
|------------------------|--------------------------------|---------------------|--------------------------|
| 🟦 Callback-last       | 🟦 Timers                      | 🟦 Event Loop       | ⬜ async.js library      |
| 🟦 Error-first         | 🟦 setImmediate                | 🟦 Async error      | ⬜ Async composition     |
| 🟦 Promise             | 🟦 nextTick                    | 🟦 try..catch       | ⬜ Rx.js                 |
| 🟦 Async function      | ⬜ AbortController             | 🟦 Non-blocking     | 🟦 Sequential async      |
| 🟦 await               | 🟦 Promise unhandled rejection | 🟦 Async I/O        | 🟦 Parallel async        |
| 🟦 Generator           | 🟦 Promise double resolve      | 🟦 Pattern Reactor  | 🟦 Promise.all           |
| 🟦 Async Generator     | 🟦 child_process               | ⬜ CAS operations   | 🟦 Promise.allSettled    |
| 🟦 Async Iterator      | 🟦 worker_threads              | ⬜ epoll            | 🟦 Promise.race          |
| 🟦 Thenable            | 🟦 Atomics                     | ⬜ kqueue           | 🟦 Promise.any           |
| 🟦 EventEmitter        | 🟦 Blockeing operations        | ⬜ Completion ports | ⬜ Web Locks API         |
| ⬜ Cancelable callback | 🟦 Non-blocking loop for Array | ⬜ Event ports      | ⬜ Async Pool            |
| ⬜ Cancelable Promise  | ⬜ High resolution clock       | 🟦 libuv            | ⬜ Thread Pool           |
| 🟦 Asynchronous Queue  | 🟦 Callback hell               | 🟦 Race conditions  | 🟦 callbackify           |
| ⬜ Future              | 🟦 Promise hell                | 🟦 Dead locks       | 🟦 promisify             |
| ⬜ Deferred            |                                | 🟦 Live locks       | ⬜ IPC                   |
| 🟦 Observer            |                                | ⬜ Actor Model      | ⬜ Channel API           |
| ⬜ Async Collector     |                                |                     | ⬜ Revealing Constructor |
| ⬜ Coroutine           |                                |                     |                          |
| ⬜ Goroutine           |                                |                     |                          |

## iOS Development specific skills
[Link to sources](https://trello.com/b/hLGyiEEE/swift-developer-roadmap)

| Level 1                     | Level 2                       | Level 3                     |
|-----------------------------|-------------------------------|-----------------------------|
| 🟦 Basic Terminal Usage     | 🟦 Carthage                   | 🟦 Concurrent Programming  |
| 🟦 Git                      | 🟦 Dynamic, Static frameworks | 🟦 Grand Central Dispatch  |
| 🟦 GitHub                   | 🟦 Value, Reference Types     | 🟦 Build Config            |
| 🟦 Xcode IDE                | 🟦 Functional Programming     | 🟦 Scheme                  |
| 🟦 Swift Playgrounds        | 🟦 Xcode Code Coverage        | 🟦 Target                  |
| 🟦 Swift Basics             | 🟦 Manual Memory Management   | 🟦 View Code               |
| 🟦 Data Structures          | 🟦 Automatic Reference Count  | 🟦 Swift Evolution         |
| 🟦 Algorithms               | 🟦 Clean Code                 | 🟦 Services & Frameworks   |
| 🟦 OOP                      | 🟦 Generic Types              | 🟦 Firebase                |
| 🟦 Foundation               | 🟦 Observers                  | 🟦 KeyedArchiver           |
| 🟦 Storyboard               | 🟦 Reactive Programming       | 🟦 Swift Package Manager   |
| 🟦 Auto Layout              | 🟦 RxSwift                    | 🟦 Fastlane                |
| 🟦 Human Interface Guideines| 🟦 SwiftUI                    | 🟦 Slather                 |
| 🟦 UIKit                    | 🟦 Combine                    | 🟦 Travis                  |
| 🟦 UIViewControllers        | 🟦 ReactiveCocoa              | 🟦 Bitrise                 |
| 🟦 ViewController Life Cycle| 🟦 Cocoa Touch                | 🟦 CircleCI                |
| 🟦 Model View Controller    | 🟦 XIB                        | 🟦 Jenkins                 |
| 🟦 Delegates                | 🟦 Dependency Injection       | 🟦 Xcode Server            |
| 🟦 Reference Cycle          | 🟦 SOLID                      | 🟦 Codecov.io              |
| 🟦 Optionals                | 🟦 Test-Driven Development    | 🟦 TCP/IP Sockets APIs     |
| 🟦 Navigation               | 🟦 Test Doubles (Mocks)       | 🟦 TLS & MTLS              |
| 🟦 Application Life Cycle   | 🟦 Clean Architecture         | 🟦 SSL Pinning             |
| 🟦 RESTful APIs             | 🟦 VIPER                      | 🟦 Security                |
| 🟦 HTTP APIs                | 🟦 Coordinators               | 🟦 Coroutines              |
| 🟦 URLSession               | 🟦 Pattern Matching           | 🟦 Command Line with Swift |
| 🟦 JSON Serialization       | 🟦 UI Tests                   | 🟦 Swift on Docker         |
| 🟦 Alamofire                | 🟦 Nimble                     | 🟦 WebFrameworks           |
| 🟦 CocoaPods                | 🟦 Quick                      | 🟦 Universal Links         |
| 🟦 Debugging                | 🟦 Core Data                  | 🟦 Fabric                  |
| 🟦 SwiftLint                | 🟦 Realm                      | 🟦 Crashlytics             |
| 🟦 Singleton                | 🟦 Plist                      | 🟦 Amplitude               |
| 🟦 Protocol-Oriented Pr.    | 🟦 Keychain                   | 🟦 Google Analytics        |
| 🟦 Local Notifications      | 🟦 Instruments                | 🟦 RIBs                    |
| 🟦 Apple Review Guideline   | 🟦 Sanitizer                  | 🟦 CoreVideo               |
| 🟦 TestFlight               | 🟦 LLDB                       | 🟦 CoreAudio               |
| 🟦 AppStore Connect         | 🟦 Diagnostics                |                            |
| 🟦 Visual Debugging         | 🟦 Provisioning Profiles      |                            |
| 🟦 Gauges                   | 🟦 Push Notifications         |                            |
| 🟦 XCTest                   | 🟦 ResponderChain             |                            |
| 🟦 Model View ViewModel     | 🟦 Multi-Touch Event Handling |                            |
| 🟦 Cloud Kit                | 🟦 Core Graphics              |                            |
|                             | 🟦 Objective-C Basics         |                            |
|                             | 🟦 Open Source Contibution    |                            |
|                             | 🟦 AVFounation                |                            |
|                             | 🟦 AudioQueueServices         |                            |

