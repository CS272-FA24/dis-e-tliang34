# Sort Books

## State:

`i` - an integer

`swapped` - a boolean value

`X` - an array

## Code:

1. Assign the pile of books to `X`.

2. Assign 1 to `i`.

3. Assign FALSE to `swapped`.

4. Go to the `i`th position in `X`.

5. If there isn't a book at position `X` + 1, then:

    a. If `swapped` is FALSE, return `X`.

    b. Otherwise, go to step 2.

6. If the book at position `i` is alphabetically greater than the book at position `i + 1`, then:

    a. Swap the books at positions `i` and `i + 1`.
    
    b. Assign TRUE to `swapped`.

7. Add 1 to `i`.

8. Go to step 4.
