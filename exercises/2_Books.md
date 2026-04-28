### 1. Write a Book class with the following attributes:

    title
    author
    number of pages
    year

### 2. Create Book instances with the following information:

| Author                | Title                         | Number of pages | Year |
|-----------------------|-------------------------------|------------------|------|
| Anonymous             | Beowulf                       | 320              | 975 |
| Niccolò Machiavelli   | The Prince                    | 140              | 1532 |
| William Shakespeare   | Hamlet                        | 160              | 1603 |
| Jane Austen           | Pride and Prejudice          | 432              | 1800 |
| Mary Shelley          | Frankenstein                 | 280              | 1818 |
| J. D. Salinger        | The Catcher in the Rye       | 255              | 1951 |

Let the number of pages and year be in integer format.

### 3. Suppose you have a list of books which represents books available at a library.

### Create a function `oldest_book` which takes a list of books as an argument and it returns the year of the oldest book from the library

Example:

```python 
>>> oldest_book(books)
>>> 975
```

### 4. Create a function `shortest_author` which takes a list of books as an argument and it returns the title of the book whose author's name is the shortest.

Example:

```python 
>>> shortest_author(books)
>>> Beowulf
```

### 5. Create a function `average_pages` which takes a list of books as an argument and prints the average number of all the books.

Example:

```python 
>>> average_pages(books)
>>> The average number of pages is: 264.5
```

### 6. Create a function `book_century` which takes a list of books as an argument and returns a dictionary in which keys are book names and values are the century in which the book was written. 

Example:

```python 
>>> book_century(books)
>>> {'Beowulf': 10, 'The Prince': 16, 'Hamlet': 17, 'Pride and Prejudice': 18, 'Frankenstein': 19, 'The Catcher in the Rye': 20}
```