# FP3: Team Declaration
DUE April 2, 2015 Wednesday (2015-04-02)

### Team Members

The given information is the real name followed by the GitHub username.

* Roy Van Liew - [**Dossar**][Dossar]
* James Kuczynski - [**DeepBlue14**][DeepBlue14]
* Yong Cho - [**YongCho**][YongCho]

### A Team Name

Deciding between the following:
* Racket Science - another team might have already thought of this.
* Schemeless Racketmen

### Project Title

Pending Title. We'd like something short but to the point.

Racket-QA: Testing Utilities for Racket QA Engineers
* Racket-Doc: Documentation Generator
* Bottle-Racket: Simple, clean GUI for changing Bottlenose Perl tests to Racket tests
* Racket-EasyTest: Simple, clean GUI for generating test cases and suites

### Project Concept

The purpose of this project is to create utilities that a QA Engineer could use when programming in Racket.

### Libraries You Plan to Use 

From what it looks like so far from the group, these are the libraries that have been used:
* Racket Graphical Interface Toolkit - `#lang racket/gui`
* Filesystem - `(require racket/file)`
* RackUnit - `(require rackunit)`
* IMAP - `(require net/imap)`

The reason why I listed IMAP is because email could also be handy with exporting test results and as a helper utility. For instance:
* Someone could create a new test suite and want to email a file with it to themselves or another person.
* An email can be sent when the test cases run, indicating that the test cases pass or fail. In my experience as a QA Engineer in Akamai, I'd see results from Daily Regressions, and emails were sent to the QA Team about what passed and what didn't.

<!-- Links -->
[Dossar]: https://github.com/Dossar
[DeepBlue14]: https://github.com/DeepBlue14
[YongCho]: https://github.com/YongCho
