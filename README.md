# Set

A set is an unordered collection where all of the contained elements are unique from one another.  Put another way a set can only contain one reference to any other object.


## Why is this important?

The notion of sets comes directly from set theory in math, and is profoundly useful in computing.  Sets can me combine with each other using set operations such as union and intersection.  These operations should be familiar to you from SQL.

##Releases

###Release 0: Write tests

Write RSpec tests to specify the behavior of the following methods of the `Set` class.

####Interface
- `new(array)` - Instantiate a new set from an optional array
- `add(element)` - Add an element to the receiver, if it's already included do nothing
- `remove(element)` - Remove an element if present in the receiver
- `iterate{ |element| block }` - iterate through all of the elements of the receiver

Remember, a set can have no duplicate elements.

###Release 1: Implement `Set`

Implement the methods from the previous release using your `ResizableArray` class. Feel free to add methods to the `ResizableArray` class to assist you in implementing `Set`.  Do _not_ use a `Hash` object in your implementation.

###Release 2: Define set operations

Write RSpec tests to specify the behavior of the following set operation methods.

- `union(set)` - Answers a new set that is the union of the receiver and param
- `intersection(set)` - Answers a new set that is the intersection of the receiver and param
- `difference(set)` - Answers a new set that is the difference between the receiver and param
- `subset?(set)` - Answers whether or not the param is a subset of the receiver

Be sure to include tests for operations involving empty sets.

###Release 3: Implement set operations

Implement the methods from the previous release.

##Resources

* [Wikipedia: Set data type](http://en.wikipedia.org/wiki/Set_%28abstract_data_type%29)
