Unfortunately-Named Programming Terms
=====================================

Because programming would be hard enough if we had good names for things.
I mean seriously.
For an activity that requires such relentless, fastidious precision of its practitioners,
it's miraculous we can even communicate at all.

If you've ever tried teaching programming to beginners, maybe you've noticed.
Or maybe this is the first time you're deliberately considering
how overloaded our terms of art are,
and are maybe surprised by what you find.

Either way, welcome!

Hope you find this interesting,
and please feel welcome to contribute.

*Note: documentating != proposing replacement*

Without further ado:

+------------+-------------------------------------------+-------------------------------------------------+
| term       | meanings                                  | issues                                          |
+============+===========================================+=================================================+
| key        | 1. unique value allowing efficient lookup | - overloaded, difficult to google               |
|            |    of associated values (e.g. in a map,   | - the metaphor works for symmetric key crypto   |
|            |    datastore, etc.)                       |   ("only those with the key can lock/unlock     |
|            | 2. (non-unique) attribute of data in a    |   access") but only causes confusion for public |
|            |    collection by which it can be ordered, |   key crypto ("I give my key out to everyone?") |
|            |    grouped, etc.                          |                                                 |
|            | 3. a secret value used for                |                                                 |
|            |    encryption/decryption/authentication   |                                                 |
|            | 4. a public value used for encryption and |                                                 |
|            |    authentication                         |                                                 |
+------------+-------------------------------------------+-------------------------------------------------+
| value      | 1. the value that a key (e.g. in a map)   | - overloaded, difficult to google               |
|            |    is associated with                     |                                                 |
|            | 2. any data (e.g. that can be stored      |                                                 |
|            |    in a variable)                         |                                                 |
+------------+-------------------------------------------+-------------------------------------------------+
| set        | 1. to assign a value                      | - overloaded, difficult to google               |
|            | 2. a collection of unique elements        |                                                 |
+------------+-------------------------------------------+-------------------------------------------------+
| map        | 1. to apply a function to a collection of | - overloaded, difficult to google               |
|            |    of elements                            |                                                 |
|            | 2. a data structure associating keys with |                                                 |
|            |    values                                 |                                                 |
+------------+-------------------------------------------+-------------------------------------------------+
| class      |                                           |                                                 |
+------------+-------------------------------------------+-------------------------------------------------+
| type       |                                           |                                                 |
+------------+-------------------------------------------+-------------------------------------------------+
| object     |                                           |                                                 |
+------------+-------------------------------------------+-------------------------------------------------+
| heap       | 1. a pool of memory managed by an         | - overloaded, difficult to google because a     |
|            |    allocator                              |   heap-tree is typically allocated on the heap, |
|            | 2. a type of tree-based data structure    |   and a memory heap is itself implemented with  |
|            |                                           |   some sort of a data structure                 |
+------------+-------------------------------------------+-------------------------------------------------+
