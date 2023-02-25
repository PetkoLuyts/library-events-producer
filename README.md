# library-events-producer
Producer microservice for the Library Inventory Application

## Library Inventory Application Architecture

When the librarian scans a new book, it goes to the post endpoint of our Microservice1, then with the kafka producer we publish it to the library-events topic. There is also a put endpoint

<img width="763" alt="Screenshot 2023-02-25 at 12 44 26" src="https://user-images.githubusercontent.com/35624159/221352657-1a49730f-a8f7-4f0c-b83a-b2f7df5bf1de.png">

* Unit tests
* Integration tests
* Error handling
