{:title "Satisfaction 25-08-2015"
 :layout :post
 :tags  ["meet"]}

### Meet #6

# Pattern matching

Clojures [core.match](https://github.com/clojure/core.match) is a great library, but unfortunately it doesn't work with top level function definitions in a way similar to multi-methods. We tried to come up with some possible solutions, but were unable to so. The most pragmatic solution suggested was to use Haskell instead.

# Containers

We had a long discussion on the current state of containers. There is a lot of excitement in this field. Currently there are a number of problems such as user namespacing that Docker has not been able to resolve, but these problems will most likely resolve over time. Many are using containers incorrectly. Containers can be designed to be very short lived firing up just to tackle the task at hand and then shutting down again - often just over a period of microseconds. Some scepticism was expressed regarding anything running on the JVM to just quickly run up..

# Go

We had a brief discussion on the Go programming language and it's use of interfaces and lack of generics.

# Functional UI design

The conversation turned to User Interface implementation. Generally UI's are very well suited to Objects relying on mutation, so trying to implement them in a functional way can be quite unsatisfying. 

