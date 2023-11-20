# thunk-operating-system

It seems commanding computers is complicated. You need developers to do complicated tasks.

* Computers can process lots of items fast, which humans are slower at. But how many things realistically do you need to do at the same time? Is all your work sequential? Can you do lots of different tasks at the same time?

* I want to define what should be the case an the computer complete work in the fastest way possible.

* Define the cases, the computer works out how to do the work.
* Import problem solvers and integrate them.
* How do you combine things together? Algebra.
* The system is based on what you can DO!

I can write what I want to be the case. Thank you for installing thunk-operating-system. This is an imaginary desktop environment and computer environment.

This is documentation for how things work.

Thunk operating system and desktop environment is:

* asynchronous driven, evented
* parallel
* data flow orientated
* queued
* scroll based
* chainable
* traversal based

An operating system desktop that is commanded by [GUI thunking](https://github.com/samsquire/gui-thunks) and state machine formulation.

executable documentation

automatic algorithm

The multiterminal. Problem space.

```
rest>
db>
io>
cpu>

```

AST boundary token mapping and recording spans

# Features

* **High performance GUIs** that can seamlessly be pointed at any data source and handle sorting, filtering and searching multiple billions of records efficiently.
* **The power of spreadsheets** Change outcomes by tweaking something and seeing its effects elsewhere.
* Well defined Feature interaction and and composeability. 
* **Clustering** 
* **Fast scalable ingest**
* **Rapid programming environment: use an interpreted language to wire things up at compile time** We wire up data flow, it's static configuration for a fast runtime: what should happen.
* **Billions runtime**
* **Good at doing the same task repeatedly** 

# Thunks are the primitive of this desktop

Thunks are like autocomplete options in a program that you can browse into without cost of execution to see how things look if you were to do it.

Whereas other traditional operating systems desktops such as in Windows, Linux, Mac have the primitives of Menus, Windows, Icons. The primitive of thunk-operating-system and desktop is the **thunk**. Thunks are hyperlinks into possible arrangements.

A thunk has a type and a number of operations that can be done on it. We can navigate through thunks without computation but we know what the shape of the thunk shall be based on any operation on it.

We can therefore create something that "looks right" by simple navigation.

# Create a unit (a div)

A unit can "do things to make them true" and interact with events.

Control loops

IntelliJ UI is strange, because the tools we use are strange

# Structured interaction programming

| Table of thunk operations | Description                   |
| ------------------------- | ----------------------------- |
| fact(parameter)           | Associate parameter with fact |
|                           |                               |



# Thunks can be moved around



# 1. Scalable architecture is sliced into threads

```

thread(1) iothread(1) send-thread = setup-send-connections | liburing_wait | dispatch_to_thread
thread(2) iothread(2) recv-thread = setup-recv-connections | liburing_wait | dispatch_to_thread
dispatch_to_thread thread(X) = parse-request | update-database | queue-broadcast

```

a global stack for my function, global variables, are they really global?

memory management between threads, closures

the essence of the problem, everything else is just logistics

make this look like that, draw diagram, can it be verified?

# 2. Visual basic for thunks

# 3. Standard data binding and layout arrangement algorithms

Draw diagrams with rectangles, layout items to rectangles automatically, allocate, or generate grid, transpose

Visual arrangements, timelines.

Just arrange colours to coloured buckets

Coloured Plots.

Interaction intersection is a program that decides what to do via plotting, moving between locations. Either raise new events that need to be plotted, handled, or reconciled. (Side by side behaviour by default) meet in the middle



```
process
window
```



# 2. Define topologies of data flow



```
```



# 3. Install behaviour

```
install | 
```



# 

# 5. Barrier runtime

```
next_free_thread = 2
task(A) thread(1) assignment(A, 1) = running_on(A, 1) | paused(A, 1)

running_on(A, 1)
thread(1)
assignment(A, 1)
thread_free(next_free_thread) = fork(A, B)
                                | send_task_to_thread(B, next_free_thread) assignment(B, next_free_thread)
                                |   running_on(B, 2)
                                    paused(B, 1)
                                    running_on(A, 1)
                               | { yield(B, returnvalue) | paused(B, 2) }
                                 { await(A, B, returnvalue) | paused(A, 1) }
                               | send_returnvalue(B, A, returnvalue) 
```

```
iothread(1) uring(1) = liburing-wait | coroutine(A) wakeup(A)

worker-thread coroutine(A) io-request(request) = send-io(1, request) | sleep(A)

worker-thread coroutine(A) yield(A) = sleep(A)
```



# 5. Vias pointers

# 6. Import scalability

# 7. Can test if things work together and know they have the expected behaviour

# 8. Value Grids

can joins represent control flow?

```
pagination      thread				overlap
authentication  io					collision-detection
authorisation   syscall				problem-space
two-pane        download			fast-composite
three-pane      line				fast-traversal
login-page		circle				image
package			menu				overlapping-regions
component		file				
install			chunk
window			chunk-hierarchy
unit			settings
object			scroll
query			pipeline			
```

direction











