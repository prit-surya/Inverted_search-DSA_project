Inverted Search - Data Structure Project


Overview
The Inverted Search project focuses on building an inverted index, a data structure that stores mappings from content, such as words or numbers, to their locations within a table, document, or set of documents. This data structure is widely used in search engines and databases to facilitate efficient full-text search.



Purpose
The primary goal of this project is to create an inverted index to allow fast full-text searches across a collection of documents. By using an inverted index, the retrieval of documents based on specific keywords or terms becomes highly efficient. However, this efficiency in searching comes at the cost of increased processing when adding new documents to the database.



Indexing Types
The project involves working with two types of indexing:



Forward Indexing:



Maps documents to the content they contain.
Example: A document is mapped to the words it includes.
Inverted Indexing:


Maps content (such as words or numbers) to their locations within documents.

Example: A word is mapped to the list of documents (and positions) in which it appears.
Features

Document Parsing: Efficiently reads and processes a set of documents to extract words or numbers.

Inverted Index Creation: Builds an inverted index by mapping each word or number to its respective document and location.

Fast Search: Enables quick retrieval of documents containing a particular word or set of words.

Scalability: Capable of handling large datasets by efficiently managing the index structure.

Usage
Add Documents: You can add documents to the dataset, and the system will automatically process the content and update the inverted index.

Search Documents: Search for a word or phrase across all indexed documents and receive results with document names and positions.



How to run project :-

check sample output pdf and instead of ./Slist.exe use ./a.out
