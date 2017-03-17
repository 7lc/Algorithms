Mergeable heaps

A mergeable heap is any data structure that supports the following five operations, in which each element has a key:

MAKE-HEAP./ creates and returns a new heap containing no elements.

INSERT.H; x/ inserts element x, whose key has already been filled in, into heap H .

MINIMUM.H/ returns a pointer to the element in heap H whose key is minimum.

EXTRACT-MIN.H/ deletes the element from heap H whose key is minimum, re- turning a pointer to the element.

UNION.H1;H2/ creates and returns a new heap that contains all the elements of heaps H1 and H2. Heaps H1 and H2 are “destroyed” by this operation.

In addition to the mergeable-heap operations above, Fibonacci heaps also support the following two operations:

DECREASE-KEY.H;x;k/ assigns to element x within heap H the new key value k, which we assume to be no greater than its current key value.1

DELETE.H; x/ deletes element x from heap H .
