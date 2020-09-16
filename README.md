# Reading Log
Repository to keep up my reading log and create / maintain reading plans and
lists

## Record format
The reading log is kept in `HaveRead.txt` file, where each row corresponds to
a book or audiobook that I've read / listened to. Each row should be
formatted as follows:

```
YYYYMMDD - Book title, автор Author's Name [ppp:rr]fs
```

where:

* `YYYYMMDD` - Date the book was finished on,
* `Book title` - self-explanatory
* `Author's Name` - self-explanatory, first name first. In case when there
  are several authors, their names are separated with `; `
* `ppp` - number of pages (0 for audiobooks)
* `rr` - rating (1-10)
* `f` - book format (`+` for books, `@` for audiobooks)
* `s` - special marks, could be many of them (`^` - have read that book before,
  `*` - really awesome title, `#` - non-fiction book)


## Reading lists and plans

The `To read` lists are constructed simply by adding (at the end of list) a
list item containing book title and its author in no particular format,
although any link to recommendation or mention is welcome. 

List items are sorted by the number of mentions. The fact that the book is in
list means only one recommendation, any following mentions are marked as `*`
signs just after the book's position in the list.

So at any given time the book, that is on top of the list, is my next candidate
to read.
