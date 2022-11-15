# Index based semantic similarity search methods in unstructured text data

Unstructured data refers to information that is not organised using a predetermined data model or schema and cannot be stored in a conventional relational database system, also known as an RDBMS. Unstructured material frequently comes in the form of text and multimedia. Emails, movies, images, webpages, audio files, and other digital media are all examples of unstructured corporate documentation.

Unstructured data makes up between 80% and 90% of the data generated and gathered by businesses, and its volumes are expanding at a rate that is many times faster than that of structured databases.

A lot of data that can be used to inform business decisions can be found in unstructured data storage. Unstructured data, however, has historically been particularly challenging to evaluate. New software tools are developing that can search through enormous amounts of data to find useful and useful business intelligence with the aid of AI and machine learning.

# Index based semantic search approach
There are several methods for search unstructured data semantically- That is by taking the actual context/meaning of the sentences.One best approach is index based approach.
Here the contents of the text data, where we need to perform the search is storing in in an index in the form of vectors. In the searching phase,the vector format of the user query is matching with the vector contents inside the index and retrive the most matching results back to the user.

# Tools used here

## For embedding purpose
   [SentenceTransformers](https://www.sbert.net/)
   ![Alt text](/Images/sbert.png?raw=true "SentenceTransformers")

## For indexing purpose
   [FAISS-CPU](https://github.com/kyamagu/faiss-wheels)

   ![Alt text](/Images/faiss.png?raw=true "FAISS-CPU")

   [NMSLIB](https://github.com/nmslib/nmslib)

   ![Alt text](/Images/nmslib.png?raw=true "NMSLIB")

   [ANNOY](https://github.com/spotify/annoy)

   ![Alt text](/Images/annoy.png?raw=true "ANNOY")
