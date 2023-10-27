Instructions for DNA lab
------------------------

## Background

You will be implementing a simple simulator for DNA splicing, using
the test-first software engineering methodology. Don't worry about the
scientific details of DNA splicing. For us, a strand of DNA is modeled
by a Java String consisting of the characters C,G,T, and A (repeated
any number of times in any order). When implementing the splicing
methods in the interface IDnaStrand, read the JavaDoc carefully, and
implement the method to the best of your ability, but you can just
ignore any details that you find confusing. The real point of this lab
is the test-first methodology, not the science of DNA splicing.

## Instructions

1.  Create a new Java project in Eclipse (or use another IDE if desired, but the instructions below assume Eclipse). Make sure to add JUnit as a
    library for this project. Any version of JUnit should be fine.
2.  Import the file [IDnaStrand.java](IDnaStrand.java) into the
    project.
3.  Create a new class, called `SimpleStrand`, which implements the
    interface `IDnaStrand`. If you use the features of Eclipse correctly
    to do this, Eclipse will automatically create stubs of all the
    methods that need to be implemented.
4.  Remember, the whole point of this lab is to write the tests
    first. Do _not_ edit the stubs of the methods in `SimpleStrand`!
5.  Create a new JUnit Test Case (search around for this option under
    File|New). Make sure to specify `SimpleStrand` as the class being
    tested. Your test class can be given any reasonable name, such as
    `SimpleStrandTest`.
6.  Now for the interesting part. Write one or more tests! Easy
    challenge: which method(s) need to be tested first? These are the
    tests you will need to write first.
7.  Implement the method(s) for which you have written test(s).
8.  Continue with this pattern: write one or more tests, then
    implement the corresponding methods. Do not edit any method in
    SimpleStrand until you have written a comprehensive test for it.

Acknowledgment: `IDnaStrand.java` is taken from the Stanford [Nifty
Assignments repository](http://nifty.stanford.edu/), and this lab
appears to have been originally authored by Richard E. Pattis of UC
Irvine. However, the file is used for a completely different purpose
here. If you're interested, you can see the full context for this file
in Duke University's [DNA splicing
lab](http://nifty.stanford.edu/2009/astrachan-dna/).
