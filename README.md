# Book Scrabble Project

## Description
The Book Scrabble Project is a multiplayer word game inspired by Scrabble. The project demonstrates advanced caching mechanisms (LRU, LFU), Bloom Filter for efficient word validation, and TCP client-server communication.

## Features
- **Word Validation:** Using Bloom Filter for fast lookups and reduced file access.
- **Caching Mechanisms:** Implemented using LRU and LFU policies for efficient memory usage.
- **Server-Client Communication:** Based on TCP sockets, allowing multiple clients to connect and interact with the server.
- **Dictionary Management:** Supports multiple files and efficient search through hashing and indexing.
- **Modular Design:** The project is divided into separate modules for better maintainability and testing.
- **Testing System:** Includes `MainTrain.java` for validating each part of the project independently.
- **Word Validation:** Using Bloom Filter for fast lookups.
- **Caching Mechanisms:** Implemented using LRU and LFU policies.
- **Server-Client Communication:** Based on TCP sockets.
- **Dictionary Management:** Supports multiple files and efficient search.

## How to Run
1. Compile the Java files in the `src/` directory.
2. Run the `MainTrain.java` file located in the `test/` directory to validate the implementation.
3. Make sure the text files are located in the `data/` directory.

## Technologies Used
- **Java**
- **Socket Programming**
- **Design Patterns:** Singleton, Factory, Observer
- **Caching Policies:** LRU, LFU
- **Bloom Filter**

## Author
Tov
