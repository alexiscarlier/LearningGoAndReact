# Learning Diary

## Overview

A record of the steps we took to learn essential features of Go and React, which we use to continually reflect on progress and plan next steps.

## Diary
How to Learn Go and React in 2 Weeks

### Day 1
We began by taking coding challenges which we were already familiar with and working on them in Go. The challenges are designed to apply key developer tools we already knew in previous languages to the new one. The first of these challenges was:
FizzBuzz, a function that prints out numbers 1 to 100, replacing multiples of 3 with ‘Fizz’, multiples of 5 with ‘Buzz’ and multiples of 15 with ‘FizzBuzz’.

#### Learning gains:
* Setting up a Go working environment
* Testing in Go, using Go’s in-built testing functions
* Creating Go executables
* Basic Go syntax

### Day 2

[Note on meetings to define MVP and group name]

We continued with our plan to tackle coding challenges to add our the list of tools:

Notebook, a command line applications that allows the user to store and view a list of strings
Hello World, a single web page served by the language which says, you guessed it, ‘Hello World’

From there, we researched

#### Learning gains:
* Object oriented programming in Go
* Using Go’s net/http package to serve web pages

### Day 3

We made a decision to have a pair working on the react front-end and two pairs working on the golang server. For the server pairs the main focus was on first understanding the architecture required to setup a websocket connection to a client and then test driving the creation of the simplest implementation for our MVP..

The react team focused on creating the front-end of our MVP and gaining visibility and knowledge on the structure and flow of react components. This was all done with the mindset of creating tests that would ultimately ensure that the features we created were thoroughly tested and grounded in a deeper understanding of the architecture.

Reached what we defined as a very minimal MVP

#### Learning gains:
* How to create a react app using yarn
* Using Go to create a websocket connection
* How to integrate RethinkDB into a Go server
* How to mock RethinkDB for Go tests



### Day 4
We carried on the structure of 2 pairs on Go and 1 pair on react. Team react is exploring testing in React today. Team Go is exploring test driving the back end server.

We had shared ‘spelunking’ session, where we went line-by-line to question the purpose of every line of code to ensure everyone in the group understood the flow.

We agreed to make a growing ‘universe’ of our code in a diagram we would all add to.

We agreed to diagram the React front-end components.

#### Learning gains:
* How to test components being rendered in react using Jest + Enzyme
