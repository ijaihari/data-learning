# Compound Data Types and Their Methods in Python

Python has four main compound (collection) data types:
- List
- Tuple
- Set
- Dictionary

Each type has its own behavior and therefore different methods.


## 1. List
- Ordered
- Mutable
- Allows duplicates
- Indexing supported

**Common methods:**
- append()
- extend()
- insert()
- remove()
- pop()
- clear()
- sort()
- reverse()
- copy()
- count()
- index()

## 2. Tuple
- Ordered
- Immutable
- Allows duplicates
- Indexing supported

**Methods:**
- count()
- index()

(Only two methods because tuples cannot be changed)

## 3. Set
- Unordered
- Mutable
- No duplicates
- No indexing

**Common methods:**
- add()
- update()
- remove()
- discard()
- pop()
- clear()
- union()
- intersection()
- difference()
- copy()

## 4. Dictionary
- Key–value pairs
- Ordered (Python 3.7+)
- Keys must be unique
- Values can repeat
- Keys must be immutable

**Common methods:**
- keys()
- values()
- items()
- get()
- update()
- pop()
- popitem()
- clear()
- copy()
- fromkeys()

## Methods shared by multiple types

| Method | Works in | Notes |
|--------|----------|-------|
| copy() | list, set, dictionary | creates shallow copy |
| clear()| list, set, dictionary | removes all elements |
| pop()  | list, set, dictionary | behavior is different |
| count() | list, tuple | counts occurrences |
| index() | list, tuple | finds element position |

## Important Differences

- `append()` exists only for lists.
- `add()` exists only for sets.
- `sort()` exists only for lists.
- `keys()`, `values()`, `items()` exist only for dictionaries.
- Tuples have only `count()` and `index()` because they are immutable.

## Summary Table

| Type | Ordered | Mutable | Allows duplicates | Indexing | Typical Use |
|------|---------|---------|------------------|----------|-------------|
| List | Yes | Yes | Yes | Yes | General collection of items |
| Tuple | Yes | No | Yes | Yes | Fixed data that should not change |
| Set | No | Yes | No | No | Unique items and mathematical set operations |
| Dictionary | Yes | Yes | Keys unique | By key | Key-value mapping |

