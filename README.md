# STL


# Queue

    push(value): Adds an element to the back of the queue.
    pop(): Removes and returns the element at the front of the queue.
    front(): Returns a reference to the element at the front without removing it.
    empty(): Checks if the queue is empty.
    size(): Returns the number of elements in the queue.

# Dequeue



    push_front(value): Adds an element to the front of the deque.
    push_back(value): Adds an element to the back of the deque.
    pop_front(): Removes and returns the element from the front.
    pop_back(): Removes and returns the element from the back.
    front(): Returns a reference to the element at the front without removing it.
    back(): Returns a reference to the element at the back without removing it.
    empty(): Checks if the deque is empty.
    size(): Returns the number of elements in the deque.

# Stack
    
    push(value): Adds an element to the top of the stack.
    pop(): Removes and returns the element from the top of the stack.
    top(): Returns a reference to the element at the top without removing it.
    empty(): Checks if the stack is empty.
    size(): Returns the number of elements in the stack.
# Map

    insert(key, value): Adds a key-value pair to the map. If the key already exists, the value is updated.
    erase(key): Removes the element with the specified key from the map.
    find(key): Returns an iterator to the element with the specified key, or end() if not found.
    at(key): Accesses the value associated with the given key. Throws an exception if the key is not found.
    operator[](key): Similar to at(), but provides implicit exception handling.
    empty(): Checks if the map is empty.
    size(): Returns the number of elements in the map.
# Set

    insert(value): Adds an element to the set. If the element already exists, nothing happens.
    erase(value): Removes the element with the specified value from the set.
    find(value): Returns an iterator to the element with the specified value, or end() if not found.
    count(value): Returns the number of occurrences of the specified value in the set (always 0 or 1, since elements are unique).
    begin() and end(): Iterators to access elements in the set, in ascending order.
    empty(): Checks if the set is empty.
    size(): Returns the number of elements in the set.
# Vector

    push_back(value): Adds an element to the end of the vector.
    pop_back(): Removes and returns the last element from the vector.
    size(): Returns the number of elements in the vector.
    empty(): Checks if the vector is empty.
    operator[](index): Accesses the element at the specified index (just like arrays).
    begin() and end(): Iterators to access the first and last elements, respectively.
    clear(): Removes all elements from the vector.
    insert(iterator, value): Inserts an element at the specified position.
    erase(iterator): Removes the element at the specified position.

