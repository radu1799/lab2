The symbol table is represented in a hash table.
The hash() function follows the implementation of hashing a string into an integer value, and then we split that by the amount of positions we have in our index, to figure out where we should store the key value pair.
The add() function uses the hash() method to add a key value pair to a specific index within our list. If values already exists within that index it tries to figure out if it should update a value. If not, it just adds the key value pair to the end of the list.
The get() function attempts to find the key within our list to return the value. If it doesn’t find it, it will raise a KeyError exception just like a normal Python dictionary does.
