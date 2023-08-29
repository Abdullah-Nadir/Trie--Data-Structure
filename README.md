
# Trie

## Learning Goals

- Learn more about data structures
- Work with a trie


## Background

This program reads data from a text file that contains the 150 most popular dog names. It creates the Trie data structure and stores all the data in the structure.

Then it uses a `check` function that asks the user to enter a name and checks if it exists in the data structure. If it exists, it returns true; otherwise, it returns false.

At the end of the program, there's a function named `unloader` that frees the memory allocated by the trie.
## Usage/Examples

Your program should behave per the examples below.

```
trie/ $ ./trie dog_names.txt
Check word: Molly
Found!
```

```
trie/ $ ./trie dog_names.txt
Check word: Lucy
Found!
```

```
trie/ $ ./trie dog_names.txt
Check word: Prudence
Not Found.
```

