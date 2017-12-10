# Learning Diary

## Overview

A record of the steps we took to learn essential features of Go and React, which we use to continually reflect on progress and plan next steps.


### Day 1 - Monday
We began by taking coding challenges which we were already familiar with and working on them in Go. The challenges are designed to take essential tools learned from previous languages and apply them to Go. The first of these challenges was:
* FizzBuzz, a function that prints out numbers 1 to 100, replacing multiples of 3 with ‘Fizz’, multiples of 5 with ‘Buzz’ and multiples of 15 with ‘FizzBuzz’.

Following our initial research into Go's features, we decided on working towards building a messaging app. This was to test our understanding and application of one of Go's most distinctive features: concurrency using 'go routines'.

#### Learning gains:
* Setting up a Go working environment
* Testing in Go, using Go’s in-built testing functions
* Top-level understanding of Go's distinctive features (go routines, static typing)
* Creating Go executables
* Basic Go syntax

#### Actions:
* Research more advanced testing tools in Go
* Research how Go can be used to serve a realtime messaging app

### Day 2 - Tuesday

Using yesterday's research, we were able to define an MVP for our messaging app. We also agreed on a name and a concept: Neighbour.ly, a communications app for local communities.

We continued with our plan to tackle coding challenges to add our the list of tools:

* Notebook, a command line applications that allows the user to store and view a list of strings
* Hello World, a single web page served by the language which says, you guessed it, ‘Hello World’

Yesterday's research indicated that a WebSocket would be the most suitable way to transfer data between client and server, since this would support a realtime, duplex connection.

#### Learning gains:
* Object oriented programming in Go
* Using Go’s net/http package to serve web pages
* Using research to define a realistic MVP

#### Actions:
* Research WebSockets, and how these would be implemented in ReactJS and Go.

### Day 3 - Wednesday

We made a decision to have a pair working on the React front-end and two pairs working on the Go server. For the server pairs the main focus was on first understanding the architecture required to setup a WebSocket connection to a client and then test driving the creation of the simplest implementation for our MVP.

The React team focused on creating the front-end of our MVP and gaining visibility and knowledge on the structure and flow of react components. This was all done with the mindset of creating tests that would ultimately ensure that the features we created were thoroughly tested and grounded in a deeper understanding of the architecture.

By the end, we reached our MVP.

#### Learning gains:
* The basic structure of a React app
* Using Go to create a WebSocket connection
* How to integrate RethinkDB into a Go server
* How to mock RethinkDB for Go tests

#### Actions:
* Consolidate our understanding of the Go server
* Define the purpose of the Client, Router, Handler and Message `structs` in the Go server


### Day 4 - Thursday

We carried on the structure of 2 pairs on Go and 1 pair on react. Team react is exploring testing in React today. Team Go is exploring test driving the back end server.

We had shared ‘spelunking’ session, where we went line-by-line to question the purpose of every line of code to ensure everyone in the group understood the flow.

We agreed to make a growing ‘universe’ of our code in a diagram we would all add to.

We agreed to diagram the React front-end components.

#### Learning gains:
* How to test components being rendered in react using Jest + Enzyme

### Day 5 - Friday

### Day 6 - Saturday

### Day 7 - Sunday

### Day 8 - Monday

### Day 9 - Tuesday

### Day 10 - Wednesday
