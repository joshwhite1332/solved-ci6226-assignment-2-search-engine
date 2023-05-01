Download Link: https://assignmentchef.com/product/solved-ci6226-assignment-2-search-engine
<br>
You are provided a dataset for this assignment, which you are free to use.  You can use your own dataset as well.

<h1>Assignment</h1>

In this assignment we continue building an information retrieval system based on the results of Assignment 1, which was a system that can output a sorted list of term-document pairs.

The task in this assignment is:

<ul>

 <li>Build an inverted index;</li>

 <li>Enable simple Boolean search; 3) Implement compression techniques.</li>

</ul>

<h2>1. Inverted Index</h2>

<strong>Input</strong>: a file with sorted term-doc pairs <strong>Output</strong>: inverted index

In this part you would need to take the file containing the sorted list of term-doc pairs and transform it into a simple inverted index.  In this assignment you <strong>don’t have to</strong> worry that the list or the inverted index can be too big for main memory; however, you can take that into account.

<strong>Bonus Points</strong>: persist the inverted index as a file so you don’t need to rebuild it every time you launch the program.

<h2>2. Boolean Search</h2>

<strong>Input</strong>: a search query, an inverted index

<strong>Output</strong>: a list of documents satisfying the query

Implement a simple AND-based Boolean search, i.e., a query “horse car phone” should be treated as “horse AND car AND phone” and return only documents that contain all three words.

<strong>Bonus Points</strong>: Implement OR and NOT in addition to AND.

<h2>3. Index Compression/Optimization</h2>

Implement compression and optimization techniques that were discussed in the lectures.  In particular, implement <em>at least</em> the Dictionary-as-a-String approach.  Implementing other techniques (blocking, front-coding, skip pointers, variable-length gap encoding) is encouraged.

Compare your search engine performance and memory requirements before and after implementing compression and optimizations.  Reflect the comparison in your report.

<strong>Bonus Points</strong>: If you implement many techniques and manage to achieve impressive savings in speed and/or memory, that may earn you bonus points.