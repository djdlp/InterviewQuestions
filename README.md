# iOS Developer Interview Questions

# General iOS questions

1) Sandbox and folders

2) App states

3) How to works Push Notifications?

4) How to run app in background?



# Memory management

1) MRC (retain, release, copy, autorelease, properties)

2) ARC (essentials, bonuses, pitfals)
3) Autorelease pools in depth (how to use, bonuses, main pool)
4) Blocks memory management (capturing self)
5) Retain cycles
6) Accessors implementations (MRC)
7) CF and NS bridging


# UIKit

1) What is UIView class? UIWindow?

2) What is the difference between frame and bounds?

3) How to works UIScrollView?

4) How to works UITableView (cells creation and caching)?

5) Explain Responder Chain pattern (hit testing)

6) UIViewController lifecycle (including before iOS 6)

7) Autolayout, size classes


# Multithreading/Asynchronous 

1) What approaches do you know?
2) Deadlock, livelock (+ examples)
3) What is GCD? How GCD works with threads (what problem solves this approach?)? Barriers, Groups, Sources, Target queues
4) What is NSOperation? Comparision GCD and NSOperation
5) Common GCD patterns (perform long running task and deliver result to UI, many readers/one writer)
6) NSRunloop (+ async/sync network connections, timers in background thread)


# CoreData

1) Explain CoreData Stack (object, context, coordinator, model)

2) Parent-child contexts

3) CoreData and multithreading

4) Faulting, uniquiness 

5) Delete rules

6) Transformable properties

7) Transient properties

8) CoreData vs SQLite (iOS 8 additions)

9) Passing managed objects between threads

10) Customization NSFetchRequest (offset, limit, predicate, attributes, etc)

11) dynamic keyword


# Collections

1) What collections do you know?

2) NSArray vs NSSet (search, enumerating, internals)

3) Weak pointer collections (general collections memory management)

4) NSArray internals (class structure layout, subclasses, private implementation)

5) Prerequisites for NSdictionary keys

6) Difference between CF and NS dictionaries 


# CoreAnimation

1) What's CALayer class?
2) CALayer and UIView interaction (and difference)
3) How to provide the content of the Layer?
4) Animation types
5) Layer trees
6) Implicit/explicit animations
7) Anchor point, position, origin and animation


# Objective-C

1) Message sending (+ forwarding)

2) Categories/Extensions

3) Class clusters

4) Method swizzling

5) Designated initializer, subclassing

6) Properties via categories

7) Literals

8) instancetype

9) Atomic and nonatomic properties (+ thread safety)

10) isa pointer

11) KVO/KVC (+compilance)

12) Formal and informal protocols

13) Metaclasses

14) Root classes (NSObject, NSProxy)

15) Exceptions and error handling

16) Equality and Identity


# Design patterns

1) MVC (passive/active) / MVP / MVVM / VIPER

2) Singleton (standard implementation

3) Delegate (examples - UITableView, UICollectionView, UIScrollView, etc)

4) Observer (KVO, Notifications)

5) Decorator

6) Immutable


