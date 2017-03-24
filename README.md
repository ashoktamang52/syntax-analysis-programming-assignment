# syntax-analysis-programming-assignment
CSCI 350 Structures of Programming Language


## How to compile the program
* `cd` `<path/to/program>`
* `make`
* `./parser` `<path/to/filename>`

### Assumptions
Following conditions will throw an error additional to error already addressed by the textbook:
1. `IDENT` followed by `IDENT`.
2. `INT_LIT` followed by `INT_LIT`.
3. `IDENT` followed by `INT_LIT` and vice-versa
