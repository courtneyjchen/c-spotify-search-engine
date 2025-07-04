# C Spotify Search Engine

*Dislaimer: The data used in the following project is for non-commercial educational and personal use.*

## Project Overview

In my personalized Spotify Search Engine project, I implemented a Spotify song management system that displays information to the user about a song query. To do so, I developed a program in C++ that reads in a Spotify Top 100 CSV file, parses the comma-delimited, quote-qualified data, stores the information into string arrays, compares the user-inputted query to the elements in the array (iteratively or recursively depending on the user's input),
and outputs details to the user about the song or artist depending on the query. 

To obtain the data, I downloaded my Spotify Top 100 data as a CSV File. I then cleaned the data in Excel (converted to UTF8 format, converted seconds to minutes, etc.) until I was left with four features: Song, Artist(s), Album, and Song Duration(min.). These would become my arrays during parsing.

The program first outputs a menu  asking the user to search by Title (iterative), Title (recursive), Artist (iterative), or Artist (recursive), also offering a 5th option, Quit. It then prompts the user to enter a song or artist name (the "query") and calls the function that was specified. In the case of iteration, the program implements a for loop until a match is found between the query and an array element. In the case of recursion, the program repeatedly calls the recursive function until the base case (the match) is achieved. Finally, the program outputs that a match is found and displays the corresponding song/artist information to the user.

The project was an opportunity for me to relate a program to my own interests and practice basics like parsing, arrays, and recursion. I enjoyed being able to model a simply activity that I conduct everyday through code, and the project really helped conceptualize how database systems process queries and display information. Furthermore, the program's functionalities can be applied to other databases, such as a student portal, city phone book, etc.
