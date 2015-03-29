# FP3: Team Declaration
DUE April 2, 2015 Wednesday (2015-04-02)

### Team Members

The given information is the real name followed by the GitHub username.

* Roy Van Liew - [**Dossar**][Dossar]
* James Kuczynski - [**DeepBlue14**][DeepBlue14]
* Yong Cho - [**YongCho**][YongCho]

### A Team Name

Racket Science

### Project Title

Racket-QA

### Project Concept

The purpose of this project is to create utilities that a QA Engineer could use when programming in Racket. A few parts we brainstorm:
* Racket-Doc: Documentation Generator
* Bottle-Racket: Simple, clean GUI for changing Bottlenose Perl tests to Racket tests
* Racket-EasyTest: Simple, clean GUI for generating test cases and suites
* Racket-QA-Mail: Sending mail to a QA team's email about test suite results

### Libraries You Plan to Use 

This list is the Library Name, followed by the require or #lang statement, followed by a brief description of its purpose.

From what it looks like so far from the group, these are the libraries that have been used:
* Racket Graphical Interface Toolkit - `#lang racket/gui` - Simple, clean windows that are user-friendly for our project applications.
* Web Server - `#lang web-server/insta` - Generating HTML to display in a web browser, similar to what doxygen does.
* Filesystem - `(require racket/file)` - Retrieving contents from files and creating new files.
* RackUnit - `(require rackunit)` - Running test suites. It also has a logging utility to look into for tracking test results.
* IMAP - `(require net/imap)` - Yong Cho should give input on this as well, being able to send email about test suite results
* STMP - `(require net/smtp)` - Yong Cho should give input on this as well, being able to send email about test suite results

<!-- Links -->
[Dossar]: https://github.com/Dossar
[DeepBlue14]: https://github.com/DeepBlue14
[YongCho]: https://github.com/YongCho
