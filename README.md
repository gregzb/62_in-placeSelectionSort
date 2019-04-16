# 62_in-placeSelectionSort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples, the time required to run the reigning champ algorithm will grow by three times. Every element is iterated through once in this algorithm, so tripling the number of elements triples the number of items that must be iterated through.

1. If the number of the elements in the input triples, the number of times that the reigning champ algorithm will be invoked  will grow by three times. The reigning champ algorithm is run once for each element, so tripling the number of elements will require tripling the number of times the reigning champ algorithm is run.

2. If the number of the elements in the input triples, the time required for the selection sort will grow by nine times. As the number of elements grows at a linear rate, the time it takes to execute the reigning champ algorithm also grows at a linear rate, and it also additionally causes the number of times the reigning champ algorithm to be run to grow linearly as well. This overall results in an O(n^2) runtime.
