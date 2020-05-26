# Web graph analysis

Let a web rappresented with a graph where the nodes are web pages, and edges are hyperlink between them

## Why?

A first attempt to organize the web pages was made by Yahoo, the idea was human-categorizes (fixed) pages, but year after year this choice began infeasible, since the categories now in too many.

The idea is to forget the human effort concering the web and the it can be seen as a huge corpus of documents, rather than human categorizes, the user SEARCH for relevant document using natural language query, under the hood there is a **information retrival techniques**, there was born web search engine.

## Information retrival 

The first web search engine was desing to use just the **content** of the document, it means that both queries and documents were mapped to the same word space.

Each word whitin the document had a score (i.e. TF-IDF), after do that, you can measure similarity between vectors, and you return the top k similar

## Web pages trustworthy

We need a way to asses the trustwortiness of a web page from the structure of the web graph.

We need to come up with an assignement of a score for each nodes(web pages)

## Page Rank

- The more incoming links a web page has the more important it's
- Links from important web pages should count more!  