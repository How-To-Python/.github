


## Python Learning Guides
**Provides a Complete learning experience for Python. Each concept has a interactive command-line guide and Jupyter Notebooks guide with hands-on examples. Each notebook is self-contained with clear learning objectives and practical examples that you can run and modify.**

### Data Structures
**Each data structure has its strengths and is optimized for different use cases.**
#### Core Python Data Structures
- [Lists](): Ordered, Mutable Collections
    - Use case: Shopping carts, todo lists, any sequence that changes
    - Use when: you need an ordered, changeable collection
- [Tuples](): Immutable Sequences
    - Use case: Coordinates, database records, function return values
    - Use when: you need an ordered, unchangeable collection
- [Dictionaries](): Key-Value Mappings
    - Use case: Configuration settings, lookup tables, JSON-like data
    - Use when: you need to map keys to values
- [Sets](): Unordered Collections of Unique Elements
    - Use case: Removing duplicates, membership testing, set operations
    - Use when: you need unique elements and set operations

#### Extended Data Structures
- [Strings](): Immutable Sequences of Characters
    - Use case: Text processing, user input, file names
- [Bytes/Bytearray](): Bytes/Bytearray
    - Use case: File I/O, network communication, binary protocols

#### Specialized Collections (from collections module)
- [Named Tuples](): Tuples with Named Fields
- [Deque](): Double-Ended Queue
- [Counter](): Counting Dictionary
- [DefaultDict](): Dictionary with Default Values

#### Scientific Computing Data Structures
- [NumPy Arrays](): Numerical computing
    - Use case: Mathematical operations, scientific computing, machine learning
    - Use for: numerical computations and mathematical operations
- [Pandas DataFrames/Series](): Data analysis
    - Use case: Data analysis, CSV/Excel handling, time series
    - Use for: data analysis and manipulation

### 📊 Python Data Structures Comparison

| Data Structure | Ordered | Mutable | Duplicates | Indexed | Use Case |
|----------------|---------|---------|------------|---------|----------|
| **List** | ✅ | ✅ | ✅ | Numeric | General sequences |
| **Tuple** | ✅ | ❌ | ✅ | Numeric | Fixed collections |
| **Set** | ❌ | ✅ | ❌ | ❌ | Unique items |
| **Dict** | ✅* | ✅ | ❌ (keys) | Keys | Key-value pairs |
| **String** | ✅ | ❌ | ✅ | Numeric | Text data |