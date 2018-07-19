# Trash-Can-Encoding
From here on, the word "trashcan" is synonymous to the word "list".

A quick trashy serialization system I made for encoding arrays &amp; trashcans of arrays.

Can technically hold individual arrays up to 255^127 + 127 bytes in length. Also can hold a max of 255^127 + 127 individual arrays in one trashcan. As such, has a theoretical max size of (255^127 + 127)^2. However, Java puts a damper on things by requiring arrays to be less than the max value of an integer in size, and computers put a damper on things by having limited amounts of memory

I might add a class for a larger array at some point so that it can theoretically hold more data. Remember, it's called a trash*can*, not a trashcannot.

Also supports nesting trashcans. Prepare for the most unsanitary matryoshka in existence.

If you use this, please don't hate me when it breaks - it tends to do that every few minutes.
