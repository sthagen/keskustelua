% On Testing
% Stefan Hagen
% 2023-12-11

# Introduction

1. Consider a Glossary
1. Unit Tests
1. Functional Tests
1. Documentation
1. Code Analysis
1. Code Review
1. Control the Merge
1. Control the Build
1. Control the Artifacts
1. ... Fill me in ...
1. Surviving the Acceptance Test

# Consider a Glossary

Talk the walk and walk the talk!

<dl>
<dt>Term</dt>
<dd>Definition to agree on</dd>
<dt>Another (*if needed*)</dt>
<dd>Definition of that one</dd>
</dl>

All together now!

... because: Naming is hard.

# Unit Tests

* Code and data
* Safeguard functions
* Make and break

# Functional Tests

* Simple use cases
* Abuse cases
* Reflect on the "what"

# Documentation

* Now, what does it do?
* Summary in one short sentence
* Longer notes there after
* Maybe add more functional tests?

# Code Analysis

* Run static analyzers
* Consider the reports
* Enhance the code?
* Add some (corner) test cases?

# Code Review

* Review your code
* Maybe ask someone else too?
* Update the code?
* Update the tests?
* Update the documentation?

# Control the Merge

Regardless of the chosen workflow:

* "Compilable" commits for long living branches
  * You may have to find nasty bugs through bisection
* Understand your history
  * Do it before you need it (reflect again and again)
* Imagine how to splice (split and merge again)
  * Can you pick a cherry?

# Control the Build

* Note the context (what goes in)
* Store the binary
* Store the context information

# Control the Artifacts

* Chain of custody
* Know how to identify your binaries
* Ingredients anyone?
  * Bill of Materials
  * Dependecy trees 

# ... Fill me in ...

* What else does your environment require?
* ...
* Fullfil or fight, your choice
* But, do not ignore!

# Survive the Acceptance Test

So now you have been invited to test the real thing?

* Note the context (names, versions, checksums, ...)
* Monitor the context
* Record the inputs and the outputs
* Assess the outputs
  * Don't do the "Ja, Ja!"
* Document in writing (for later support)
* Can be short or long - your choice
  * Your own safe version of the "past"

Easy! Right?
