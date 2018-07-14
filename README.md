A python MapReduce program to :
1. Word count, 
2. Set difference

Limitations:-
-There are, of course, faster implementations for word count and set difference on a single machine.
-SetDifference will always just start with just two records
-In this MapReduce system, all mappers will complete before any reducers start (this allows us to track the output of the mappers more clearly).