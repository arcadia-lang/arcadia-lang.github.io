# <x-trans>Syntactic structures</x-trans>

<x-trans>We will start our analysis with sentences.</x-trans>
<x-trans>A sentence is the largest unit that has a syntactic structure.</x-trans>
<x-trans>Bigger parts of a passage still have structure, but it's not a structure that is defined by the zerita syntax.</x-trans>

<x-trans>A sentence is a sequence of clauses connected with words like "&{i}" (and).</x-trans>
<x-trans>A clause is the smallest part of the sentence that express something, for example a command (Just do it), a conclusion (the butler did it), a question (can you do it?), a description of the state of the world (it's raining men).</x-trans>

<x-trans>This informal distinction comes with some interesting edge cases.</x-trans>
<x-trans>Consider the following sentences:</x-trans>

- _<x-trans>You study hard and you will pass your exams.</x-trans>_
- _<x-trans>If you study hard, then you will pass your exams.</x-trans>_
- _<x-trans>If you study hard, then you will pass your exams, else you'll fail.</x-trans>_

<x-trans>How many clauses does each of the sentences have?</x-trans>
<x-trans>If they are more than one, are they treated as equals?</x-trans>

<x-trans>The approach that zerita takes is sentences have nodes, and all nodes are equal.</x-trans>
<x-trans>There is no main node.</x-trans>
<x-trans>Not all nodes are present, and there are phantom nodes.</x-trans>
<x-trans>Each node contains at least one a clause.</x-trans>
<x-trans>It contains one main clause and any number of subordinate ones.</x-trans>

<x-trans>Let's split the above examples in nodes and each node in clauses.</x-trans>

- _<x-trans>You study hard and you will pass your exams.</x-trans>_
    - **<x-trans>first node</x-trans>:** <x-trans>you study hard</x-trans>
    - **<x-trans>node connector</x-trans>:** <x-trans>and</x-trans>
    - **<x-trans>second node</x-trans>:** <x-trans>you will pass your exams</x-trans>
- _<x-trans>If you study hard, then you will pass your exams.</x-trans>_
    - **<x-trans>first node</x-trans>:** <x-trans>if you study hard, then you will pass your exams</x-trans>
        - **<x-trans>subordinate clause</x-trans>:** <x-trans>if you study hard</x-trans>
        - **<x-trans>clause connector</x-trans>:** <x-trans>then</x-trans>
        - **<x-trans>main clause</x-trans>:** <x-trans>you will pass your exams</x-trans>
- _<x-trans>If you study hard, then you will pass your exams, else you'll fail.</x-trans>_
    - **<x-trans>first node</x-trans>:** <x-trans>if you study hard, then you will pass your exams</x-trans>
        - **<x-trans>subordinate clause</x-trans>:** <x-trans>if you study hard</x-trans>
        - **<x-trans>clause connector</x-trans>:** <x-trans>then</x-trans>
        - **<x-trans>main clause</x-trans>:** <x-trans>you will pass your exams</x-trans>
    - **<x-trans>node connector</x-trans>:** <x-trans>else</x-trans>
    - **<x-trans>second node</x-trans>:**
        - **<x-trans>subordinate phantom clause</x-trans>:** <x-trans>if you don't study hard</x-trans>
        - **<x-trans>main clause</x-trans>:** <x-trans>you'll fail</x-trans>

<x-trans>The final multi-word syntactic structure that we focus on, is the phrase, which is just a sequence of connected words, for example "the big bad wolf".</x-trans>
