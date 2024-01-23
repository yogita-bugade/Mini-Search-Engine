<h1>Mini Search Engine</h1>

<b>Search engines play a crucial role in extracting relevant information from the vast World Wide Web. A simplified search engine, developed using trie data structure, is explored in this project.
</b>
<br />
<br />

<p align="center">
<img src="https://i.imgur.com/osJ7AhB.png" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>

<h2>Development Tools and Data Structures</h2>

- <b>Web Crawler:</b> Utilizes Trie Data Structure and LinkedList.
- <b>Ranking Occurrence:</b> mplements Hashset, List, Set, and String#indexOf.
- <b>Word Search:</b> Incorporates Trie Data Structure, Hashset, and LinkedList.
- <b>HTML to Text Conversio:</b> Uses JSoup.
- <b>Execution Time:</b> Monitored using currentTimeMillis.
- <b>StopWords Handling:</b> Employs Arrays and List.

<h2>Description</h2> 

<b>Trie Characteristics</b> <br />
- A trie, a k-ary search tree, efficiently stores and searches for keys in a set. It significantly reduces search complexity to an optimal level based on the key length

<b>Word Ranking</b> <br />
- Ranking is determined by the number of occurrences of a word on a page, using String#indexOf. Hashset is used to count word occurrences, and a HashMap displays their counts.

<b>Searching with Trie</b> <br />
- The search operation in the trie involves a comparison of characters, proceeding down the trie. The search concludes either at the end of a string or when a key is absent. Hashset is employed to count word occurrences, and stop words are eliminated during processing.

<b>Approach</b> <br />
- Reads sample URLs from Input.txt file.
- Crawls web pages using a web crawler, fetching URLs with a limit of 20 pages.
- Searches for words entered by the user, eliminating stop words.
- Utilizes trie data structure to store and search for words.
- Calculates word occurrences based on String#indexOf.
- Displays list of URLs containing the searched word.

<b>Boundary Conditions</b> <br />
-  The project has been tested for various boundary conditions to ensure robust functionality and reliability.

<p align="center">
<img src="https://i.imgur.com/Xgd1U01.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>Conclusion:</h2> This mini search engine, powered by trie data structure, demonstrates efficient information retrieval from web pages. The implementation leverages various data structures and technologies, providing a solid foundation for further development and optimization.
<br />
<br />
<b>References:</b> https://jsoup.org/download
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
