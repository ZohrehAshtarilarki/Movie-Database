# Movie Database Project

## Overview

This project is a comprehensive Movie Database application developed in C++ by a team of four students at De Anza College. The application utilizes Hashing and Binary Search Trees (BST) to efficiently sort and manage a collection of movies. Movies are organized by their unique IMDb codes and titles, facilitating efficient storage, retrieval, and output operations.

## Features

- **Efficient Data Management:** Utilizes Hashing and Binary Search Trees to organize and manage movies.
- **Unique Identification:** Uses IMDb codes as unique identifiers to signify the release order of movies.
- **Optimized Retrieval:** Implements primary (IMDb codes) and secondary (movie titles) keys for efficient data retrieval.
- **Rehashing Mechanism:** Handles hash table load factors to minimize collisions and maintain robust data management.
- **Comprehensive Debugging:** Ensures data integrity and usability through extensive debugging and testing.

## Team Members

- **Giovany Calleja:** Team coordination, file documentation, project presentation, menu functions, and output functions.
- **Han Qiang:** BST algorithms, file I/O operations, BinaryNode.h, BinaryTree.h, BinarySearchTree.h, and debugging.
- **Zohreh Ashtarilarki:** Hashing algorithms, HashNode.h, HashTable.h, rehashing mechanisms, and debugging.
- **Sabrina Diaz-Erazo:** Screen output functions, primary search manager, secondary key manager, display manager, and undo delete function.

## Project Structure

- **Application Data:**
  - `Movie.h`: Contains variables (IMDb code, Title, Year, Director, Rating, Genre)
- **Source Files:**
  - `main.cpp`
  - `BinaryNode.h`
  - `BinarySearchTree.h`
  - `BinaryTree.h`
  - `HashNode.h`
  - `HashTable.h`
  - `StackADT.h`
- **Data Files:**
  - `moviesTest.txt`

## Installation and Usage

### Prerequisites

Ensure you have the following installed on your system:
- GCC (GNU Compiler Collection)
- Git

### Steps

1. **Clone the repository:**
  
   git clone https://github.com/your-username/movie-database.git
   

2. **Navigate to the project directory:**
   
   cd movie-database
   
   
3. **Compile the project:**
   
   g++ main.cpp -o movie-database
   
   
4. **Run the executable:**
   
   ./movie-database
  
   
### Running the Application

Upon running the executable, you will be presented with a menu-driven interface that allows you to perform the following operations:

- **Add New Data:** Insert new movie records into the database.
- **Delete Data:** Remove existing movie records from the database.
- **Find and Display:** Search for a specific movie using primary (IMDb code) or secondary (movie title) keys.
- **List Data:** Display movies sorted by secondary keys (titles).
- **Write Data to File:** Save the current state of the database to a file named `NewMovies.txt`.
- **Statistics:** Display statistical information about the database.
- **Undo Delete:** Reverse the last delete operation using Stack ADT.
- **Help:** Display the available menu options.
- **Exit:** Close the application.


## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure your code adheres to the project's coding standards and includes relevant documentation.

## License

This project is licensed under the Apache License. See the `LICENSE` file for more details.

## Acknowledgments

We would like to thank our instructor and classmates for their support and feedback throughout the development of this project.


