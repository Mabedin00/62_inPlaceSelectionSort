# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will grow by 3x. Since the reigning champ algorithm is run
once per element, the number will also triple.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked
will grow by 3x. In this case the number of invocation
is equal to the number of time the algorithm is run.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by 3x. Since the reigning algorithm is invoked
3x more it will also take 3x more time.
[Justify, in about 2 sentences.]
