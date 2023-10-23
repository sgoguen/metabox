# Metbox - LLM Runtime Environment

What would it look like if we created a development environment and programming language tailored to the strengths
and weaknesses of an LLM?

Currently, LLMs are expected to write correct programs in one shot and lacks essential tools a human programmer has:

1. A Feedback Loop
2. Time
3. Memory

## Goal

Explore this question and try to prototype one or more concepts that attempt to address these weaknesses.

## Premises

Humans benefit from all types of tools and techniques when developing software.  Here's an incomplete list:

* Unit Testing - Allows programmers to verify their programs against a diverse set of input or data points to verify the program is working as expected.
* Type Systems - Can reduce runtime errors caused by type mismatching at a minimum. Advanced type systems can assist in proving behavior.
* Code Coverage - Highlights parts of the program not covered by tests
* Assertions - Halts the program when the program doesn't work
* Logging - Provides a searchable output of errors and behaviors.
* Debuggers - Allows a developer to stop the execution upon an line number or condition and evaulate what it actually happening.
* Profiling - Provides feedback into the performance, memory usage, or other operational aspect of the program.

While these are tools that are designed for humans:  How can some of these tools be retrofitted to assist LLMs?

What if we rethought everything from the ground-up and created a symbolic/sandboxed language for an LLM?  
Do we create a Lisp, an ML, a Haskell?

What if we started with something from something from the [PL Zoo](https://plzoo.andrej.com/)?
