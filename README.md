# thunk-operating-system

To create a group of behaviour, you create a thunk:

```
thunk 
```

To enable a new feature in the thunk, open the command line and type

```
install <feature name url>
```

To install a piece of software from an organisation:

```
install @organisation/software-name
```

Thunks can placeholder.

Thunks compose.

Thunks might have a stack, or might not.

# Thunk orderise



# Token boundarise

# Graph edit

the graph is how things work at the moment, you can move it around and keep the same behaviour.



# We define what we want and the computer fulfils it

Sequences we tap into

Scheduling easy, optaplanner







# computers are just logistics

It seems commanding computers is complicated. You need developers to do complicated tasks. But does that have to be the case?

* Computers can process lots of items fast, which humans are slower at. But how many things realistically do you need to do at the same time? Is all your work sequential? Can you do lots of different tasks at the same time that still results in something useful?

* I want to define what should be the case and the computer to complete this work in the fastest way possible, while maintaining all the cases I've given it. Each case is similar to a rule.

* Define the cases, the computer works out how to do the work. This is similar to SQL.
* Import efficient problem solver engines and integrate them. There is tradeoff in computing between **compiled languages and interpreted languages**. Interpreted languages are fast to develop for and allow complicated data flow patterns to be created with a lot less effort. Compiled languages are far more performant and more rigid.
* How do you combine things together? Algebra. Linear algebra and kinematics and rotations.
* The system is based on what you can DO!
* Useful queries, useful patterns
* Desired state checkers (types)
* Multiline REPL, constraints, combine characteristics together
* High level AST
* A useful task to do to the code while not doing anything.
* Placeholder all the things.
* Lines represent traversals
* File system is just a high level dispatch.
* Apply a transformation to a contexts, which is a region on a timeline.
* Can merge and divide contexts.
* Defining temporal transformations over sets. Temporal Joins are synchronization. Iterators that are aligned.
* Event Relationships/joins that cut across multiple objects and produce their own sequence of behaviours. Parsing? Like a table row/column + shape.
* Just wire things together.
* Positions at X times.

I can write what I want to be the case. Thank you for installing thunk-operating-system. This is an imaginary desktop environment and computer environment.

This is documentation for how things work.

# Text interface

Rope structure or piece table for fast inserts at any point and fast iteration on a struct

```
struct Name {
	struct Something *else;
};


```



```
render | dirty rerender
detect-dirty-sections | rerender-dirty
detect-code-that-ran token-boundarise
detect-changes

scan-filesystem | start-coroutines

http-request-received | parse-http-request | send-to-application-server

handles




```

message passing

autoinstancing

call stack is a tree, lifetime?

Can paginate within a text interface.

```
record:1
	indented
	indented
```

Parsed into:

```
record {
	
}
```

real time strategy grid rendering, text based



# What do you want to do?

* I want to display lots of things very fast.
* I want to accept lots of traffic for the minimum cost.
* I want to compile and make changes extremely fast.
* I want low latency.
* I want bottlenecks to be avoided.
* I want to compile incrementally.
* I want to define behaviours and fuse them together.
* I want architecture to be transformable.
* I want tradeoffs to be pickable.
* I want data structures to be easy to clone.
* I want serialization that is performant.
* There's an AST for that.

```
```

effects without a stack?

types are the valuable thing

useful tables, placeholders

# File system object pipeline

buffered reader, line reader, etc

Stacks mini processes

# Desktop environment

Thunk operating system is:

* **Asynchronous driven, evented** The computer is always doing things in the background.
* **Parallel** The computer is doing multiple things at the same time.
* **Data flow and logistics orientated** 
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

* **High performance GUIs** that can seamlessly be pointed at any data source and handle sorting, filtering and searching and navigating multiple billions of records efficiently.
* **The power of spreadsheets** Change outcomes by tweaking something and seeing its effects elsewhere.
* Well defined Feature interaction and and composeability. 
* **Clustering** 
* **Fast scalable ingest**
* **Rapid programming environment: use an interpreted language to wire things up at compile time** We wire up data flow, it's static configuration for a fast runtime: what should happen.
* **Billions runtime and traversal** 
* **Good at doing the same task repeatedly** 

# Low tech scalable

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
pagination      thread				overlap					interpolation
authentication  io					collision-detection		channel
authorisation   syscall				problem-space			event-grid
two-pane        download			fast-composite-wayland	reductions
three-pane      line				fast-traversal			stacks
login-page		circle				image					loops
package			menu				overlapping-regions		async
component		file				lease					behaviour-stacks
install			chunk				lock					server
window			chunk-hierarchy		cache					protocol
unit			settings			load-balance			stream
object			scroll				shard					upload
query			pipeline			timeline				
```

can a token stream decide what to dispatch on

compositional interleaving

problem is code is a tree

refcount for lifetime for group of objects



```
fact1(a, b, c)
fact2(d, e, f)
fact1(one, two, three) | fact2(four, two, five) | fact3(three, seven eight)
fact1#two.b -> fact2#two.e
```

expand to variables interfaces, match at any hierarchy of stack of traversal

behaviour stack is parameterised, everything is a closure

```
https-server
	request
	response
authentication
authorisation
```

everything raises events, event bus

biformation async/sync

direction

sparse graphs/maps

compositional behaviour

functional programming mapping on each side of the behaviour of one of these behaviours

monad hierarchy, things can be wrapped and maintain properties of the things inside and outside simultaneously.



```
										
										
									
										
										
									three-tier-multithreaded-architecture
										
										
										
										
										
```



# Beautiful interactions







Thunks are configured with URLs
