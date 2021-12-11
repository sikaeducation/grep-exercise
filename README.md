# Intro to `grep`

`grep` is a powerful command that can search through text output for 
matching text, or patterns of text.

Tasks:

1. List all books that were written by "Dan Brown"
1. Using a single command, create a new file called `sorted_books.txt` that contains a list of the books in `books.txt` by sorted by title.
1. Using a single command, create a new file called `books_by_george_orwell.txt` which should only contain those books by George Orwell, sorted by title.

## CHALLENGE**

Create a new file called `authors.txt` which lists only the authors of the books, 
alphabetized by first name. The list should be unique (i.e. Dan Brown is not listed twice) 
and should be numbered. Your output should look something like this:

```
1: Dan Brown
2: Ernest Hemingway
3: George Orwell
4: Harper Lee
5: J.D. Salinger
6: J.K. Rowling
7: J.R.R. Tolkien
8: Khaled Hosseini
9: Mark Twain
10: Mary Shelley
11: Neil Gaiman
12: Ray Bradbury
13: Suzanne Collins
```

> HINT: you will need to use the `.*` wildcard to complete this challenge.
In grep `.` means 'match any single character" and `.*` means match any number of any 
character. `.*:` means match any number of any character until we find a colon. `.*F` 
means match any number of any characters until we find a capital F.
