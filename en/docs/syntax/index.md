# Syntactic structures

We will start our analysis with sentences.
A sentence is the largest unit that has a syntactic structure.
Bigger parts of a passage still have structure, but it's not a structure that is defined by the zerita syntax.

A sentence is a sequence of clauses connected with words like "i" (and).
A clause is the smallest part of the sentence that express something, for example a command (Just do it), a conclusion (the butler did it), a question (can you do it?), a description of the state of the world (it's raining men).

This informal distinction comes with some interesting edge cases.
Consider the following sentences:

- _You study hard and you will pass your exams._
- _If you study hard, then you will pass your exams._
- _If you study hard, then you will pass your exams, else you'll fail._

How many clauses does each of the sentences have?
If they are more than one, are they treated as equals?

The approach that zerita takes is sentences have nodes, and all nodes are equal.
There is no main node.
Not all nodes are present, and there are phantom nodes.
Each node contains at least one a clause.
It contains one main clause and any number of subordinate ones.

Let's split the above examples in nodes and each node in clauses.

- _You study hard and you will pass your exams._
    - **first node:** you study hard
    - **node connector:** and
    - **second node:** you will pass your exams
- _If you study hard, then you will pass your exams._
    - **first node:** if you study hard, then you will pass your exams
        - **subordinate clause:** if you study hard
        - **clause connector:** then
        - **main clause:** you will pass your exams
- _If you study hard, then you will pass your exams, else you'll fail._
    - **first node:** if you study hard, then you will pass your exams
        - **subordinate clause:** if you study hard
        - **clause connector:** then
        - **main clause:** you will pass your exams
    - **node connector:** else
    - **second node:**
        - **subordinate phantom clause:** if you don't study hard
        - **main clause:** you'll fail

The final multi-word syntactic structure that we focus on, is the phrase, which is just a sequence of connected words, for example "the big bad wolf".
