# OS-Web-Technologies-Learnings
OS + Web Technologies

- RAID (Redundant Array of Independent Disks) v/s (equivalent to) Single Large Expensive Disk (SLED).

## 3-30-2020
- Cache(SRAM) -> Main Memory(DRAM) -> Disk Storage (Magnetic + SDD).
- DDR , QDR (Double Data Rate, Quad Data Rate)
- Cache managed by Hardware, Main Memory managed by OS Memory Management, and Disk managed by OS
- Base and Limit Registers comparison : Dynamic translation of virtual memory to physical memory - how important is relocation?
- Data and code segements


## 3-26-2020
- Tree Shaking : https://developer.mozilla.org/en-US/docs/Glossary/Tree_shaking

## NoSQL databases
- key value pairs based ; Redis, mongoDB, DynamoDB
- When should we use NoSQL?
  Though NoSQL databases have been optimized to handle applications dealing with huge volumes of data, it is important to keep in mind that we explicity know which common queries are w.r.t specific use cases.
[DynamoDB AWS Recommendations](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/bp-general-nosql-design.html#bp-general-nosql-design-vs-relational)
- "Relational DB's are optimized for flexible querying".

## JavaScript
- Event Loop - Async, Wait, and CallBack
- How efficient are Promises?

## React
- open source UI framework developed by Facebook
- UI considered as collection of components
- Components are like functions that take Props as input
- React has an Unidirection flow of logic
- JSX - supports HTML embedding inside ES5 JS code
- Virtual DOM <- copy of tree structure of original DOM (Document Object Model)
- React based apps can be considered as "View" part in model view controller so React apps are easily portable
- React v/s Angular?

## Accelerated Mobile Pages (AMP's)

## Service Workers
- Service workers and push notifications - subscriptions, and event listeners.

## MVC v/s MVVM
- MVC : Model View Controller
- MVVM : Model View ViewModel - Ideal for single page web-apps

## Progressive Web Apps
- Progressive web apps v/s Native apps
- PWA are indexed better in search engines

## REST
- Sessions stored on Client Side
- Client Side Rendering? Google Lite - reduce load on Server? Cache Data?

## Scheduling Algorithms
- Batch : FCFS, Shortest Job First, Shortest Remaining Time First (Pre-emption)
  Reduce Turnaround Time, Increase Throughput
- Interactive : Optimize response time, pre-emption  
- Round Robin
- Quantum Size > CPU Burst Size
  

## TSL (Test and Set Lock)

## Peterson Solution

## Process State Model
  Blocked -> Ready -> Running
  
## ReadyQ
- effective_priority() returns dynamic priority
