# awesome-language-specs
A one-stop shop for everything programming language specifications, references, and test suites. 

## Why?
I have two reasons for starting this project:
* Programming language specifications, espicially older ones, can be painfully
hard to find if you aren't "in" on a specific language.
* I enjoy fantisizing about implementing a languange and then never actually
doing it or stopping early on because something else has caught my fancy.

**You** on the other hand may find this project useful for a few reasons:
* Language specs are hard to find.
* Having a bunch of specs in one place makes it easy to study language
design.
* You can see how the design of a language has changed over time.

## What is any of this stuff anyway?
A *programming language specification* is a lot like a blueprint. It describes
a language's design, including syntax, features, and runtime details. It's written
by the creators of a programming language so that you can understand how it functions
at a low level in order to write an implementation or hack on an existing one. Not all
languages have one, but they are extremely useful for compiler and interpreter writers
and help to justify a language's existance and design.

A *programming language reference* acts as a language's manual. It gives the end-user
a high-level overview of the language and helps them to learn how to write in it and
make good use of its features. Most users of a language will likely reference (heh)
the reference and never touch the specification, as the former is much more practical
for daily usage of a language. Most programming languages have one; it would be really
annoying to learn a language that has no documentation. If you're trying to implement
a programming language, it's likely in your best interest to read the reference first
before jumping headfirst if you're not already familiar with it.

An *implementation* is a piece of software which implements (heheh) a specification.
Most languages have a *model* implementation which most users are expected to use and
can help implementers get a feel for the architecture of a langauge. Think Python and
CPython, or C# and .NET, or Java and Java SE. Some languages, however, don't
have a model implementation, like C (GCC, Clang) and JavaScript (SpiderMonkey, V8).
Not all implementations follow the spec word-for-word: some are intentionally 
incomplete, only wanting to maintain a "core" set of features, others extend it,
and others still radically change a language just to experiment.

A *test suite* allows an implementer to test if their implementation functions as the
specification intends. They are usually written in the language described by the
specification itself and come with a *harness* which allows one to hook up the test
suite to their implementation. Some languages may decide to specify themselves using
only a test suite along side a reference.

## Notation
This document is generally organized like this:
* Major Section (Specs, Implementations, Suites)
	* Language Name (alphabetical order)
		* Language Version (reverse chronological order)
			* Links to specfication and other relevant links

## Specifications

### General Resources
* Wikipedia: https://en.wikipedia.org/wiki/Programming_language_specification
* ISO 35.060 - Languages used in information technology: https://www.iso.org/ics/35.060/x/
* IEEE 35.060 - Languages used in information technology: https://ieeexplore.ieee.org/search/searchresult.jsp?queryText=%22Standards%20ICS%20Terms%22:35.060&matchBoolean=true&searchField=Search_All
* Ecma International Standards - Software engineering and interfaces: https://www.ecma-international.org/publications-and-standards/standards/?order=category#Software-engineering-and-interfaces

### [Java](https://java.com/en/)

#### SE 17 (September 2021)
* Language: https://docs.oracle.com/javase/specs/jls/se17/html/index.html
* Virtual Machine: https://docs.oracle.com/javase/specs/jvms/se17/html/index.html
* Java Speifiation Request: https://jcp.org/en/jsr/summary?id=392
* Wikipedia: https://en.wikipedia.org/wiki/Java_version_history#Java_17

#### SE 16 (March 2021)
* Language: https://docs.oracle.com/javase/specs/jls/se16/html/index.html
* Virtual Machine: https://docs.oracle.com/javase/specs/jvms/se16/html/index.html
* Java Speifiation Request: https://jcp.org/en/jsr/summary?id=391
* Wikipedia: https://en.wikipedia.org/wiki/Java_version_history#Java_16

#### SE 15 (September 2020)
* Language: https://docs.oracle.com/javase/specs/jls/se15/html/index.html
* Virtual Machine: https://docs.oracle.com/javase/specs/jvms/se15/html/index.html
* Java Speifiation Request: https://jcp.org/en/jsr/summary?id=390
* Wikipedia: https://en.wikipedia.org/wiki/Java_version_history#Java_15

#### SE 14 (March 2020)
* Language: https://docs.oracle.com/javase/specs/jls/se14/html/index.html
* Virtual Machine: https://docs.oracle.com/javase/specs/jvms/se14/html/index.html
* Java Speifiation Request: https://jcp.org/en/jsr/summary?id=389
* Wikipedia: https://en.wikipedia.org/wiki/Java_version_history#Java_14

#### SE 13 (September 2019)
* Language: https://docs.oracle.com/javase/specs/jls/se13/html/index.html
* Virtual Machine: https://docs.oracle.com/javase/specs/jvms/se13/html/index.html
* Java Speifiation Request: https://jcp.org/en/jsr/summary?id=388
* Wikipedia: https://en.wikipedia.org/wiki/Java_version_history#Java_13

#### SE 12 (March 2019)
* Language: https://docs.oracle.com/javase/specs/jls/se12/html/index.html
* Virtual Machine: https://docs.oracle.com/javase/specs/jvms/se12/html/index.html
* Java Speifiation Request: https://jcp.org/en/jsr/summary?id=386
* Wikipedia: https://en.wikipedia.org/wiki/Java_version_history#Java_12

#### SE 11 (September 2018)
* Language: https://docs.oracle.com/javase/specs/jls/se11/html/index.html
* Virtual Machine: https://docs.oracle.com/javase/specs/jvms/se11/html/index.html
* Java Speifiation Request: https://jcp.org/en/jsr/summary?id=384
* Wikipedia: https://en.wikipedia.org/wiki/Java_version_history#Java_11

#### SE 10 (March 2018)
* Language: https://docs.oracle.com/javase/specs/jls/se10/html/index.html
* Virtual Machine: https://docs.oracle.com/javase/specs/jvms/se10/html/index.html
* Java Speifiation Request: https://jcp.org/en/jsr/summary?id=383
* Wikipedia: https://en.wikipedia.org/wiki/Java_version_history#Java_10

#### SE 9 (September 2017)
* Language: https://docs.oracle.com/javase/specs/jls/se9/html/index.html
* Virtual Machine: https://docs.oracle.com/javase/specs/jvms/se9/html/index.html
* Java Speifiation Request: https://jcp.org/en/jsr/summary?id=379
* Wikipedia: https://en.wikipedia.org/wiki/Java_version_history#Java_9

#### SE 8 (March 2014)
* Language: https://docs.oracle.com/javase/specs/jls/se8/html/index.html
* Virtual Machine: https://docs.oracle.com/javase/specs/jvms/se8/html/index.html
* Java Speifiation Request: https://jcp.org/en/jsr/summary?id=337
* Wikipedia: https://en.wikipedia.org/wiki/Java_version_history#Java_8

#### SE 7 (July 2011)
* Language: https://docs.oracle.com/javase/specs/jls/se7/html/index.html
* Virtual Machine: https://docs.oracle.com/javase/specs/jvms/se7/html/index.html
	* Update (March 2015): http://jcp.org/aboutJava/communityprocess/mrel/jsr336/index.html
* Java Speifiation Request: https://jcp.org/en/jsr/summary?id=336
* Wikipedia: https://en.wikipedia.org/wiki/Java_version_history#Java_7

#### SE 6 (December 2006)
* Language: https://docs.oracle.com/javase/specs/jls/se6/html/j3TOC.html
* Virtual Machine: https://docs.oracle.com/javase/specs/jvms/se6/html/VMSpecTOC.doc.html
	* Update (SE 5.0): https://jcp.org/aboutJava/communityprocess/maintenance/jsr924/index.html
	* Update (SE 6): https://jcp.org/aboutJava/communityprocess/maintenance/jsr924/index2.html
	* Update (March 2015): https://jcp.org/aboutJava/communityprocess/mrel/jsr270/index.html
* Java Speifiation Request: https://jcp.org/en/jsr/summary?id=270
* Wikipedia: https://en.wikipedia.org/wiki/Java_version_history#Java_6
