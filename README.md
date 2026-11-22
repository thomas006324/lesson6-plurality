# Lesson 6: Plurality (IT 145-5)

**plurality.c** runs a plurality election. Candidates are given as command-line arguments and stored in an array of `candidate` structs (name and vote count). `vote` finds a candidate by name and adds one vote, returning false for an invalid name. `print_winner` makes two passes: the first finds the highest vote total, the second prints every candidate with that total, so ties print all winners.

Compile and run:

    make plurality
    ./plurality Alice Bob Charlie
