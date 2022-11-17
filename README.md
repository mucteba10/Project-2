# Project-2
The purpose of this assignment is to write a program to implement autocomplete for a given set of n strings and
nonnegative weights. That is, given a prefix, find all strings in the set that start with the prefix, in descending order of
weight.

Autocomplete is an important feature of many modern applications. As the user types, the program predicts the complete
query (typically a word or phrase) that the user intends to type. Autocomplete is most effective when there are a limited
number of likely queries. For example, the Internet Movie Database uses it to display the names of movies as the user types;
search engines use it to display suggestions as the user enters web search queries; cell phones use it to speed up text input.

The performance of autocomplete functionality is critical in many systems. For example, consider a search engine which runs
an autocomplete application on a server farm. According to one study, the application has only about 50ms to return a list
of suggestions for it to be useful to the user. Moreover, in principle, it must perform this computation for every keystroke
typed into the search bar and for every user !
In this assignment, you will implement autocomplete by sorting the queries in lexicographic order; using binary search to
find the set of queries that start with a given prefix; and sorting the matching queries in descending order by weight.

Die.java: (Comparable Six-sided Die) Implement a comparable data type called Die that represents a six-sided die and
supports the following API.

Location.java: (Comparable Geo Location) Implement an immutable data type called Location that represents a location on
Earth and supports the following API.
 
Point3D.java: (Comparable 3D Point) Implement an immutable data type called Point3D that represents a point in 3D and
supports the following API:

BinarySearchDeluxe.java: (Binary Search Deluxe) When binary searching a sorted array that contains more than one key equal to the
search key, the client may want to know the index of either the first or the last such key. Accordingly, implement a library
called BinarySearchDeluxe with the following API:


Autocomplete.java: (Autocomplete) In this part, you will implement a data type that provides autocomplete functionality for a
given set of string and weights, using Term and BinarySearchDeluxe. To do so, sort the terms in lexicographic order; use binary
search to find the set of terms that start with a given prefix; and sort the matching terms in descending order by weight.
Organize your program by creating an immutable data type called Autocomplete with the following API:
