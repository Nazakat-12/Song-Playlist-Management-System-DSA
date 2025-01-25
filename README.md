# Song-Playlist-Management-System-DSA
Playlist Management System (DSA Project)
Overview
The Playlist Management System is a console-based application designed to manage a collection of songs. This project leverages basic data structures and algorithms to manage the playlist, allowing users to add, delete, search, and play songs. The system also supports the ability to load songs from a file, sort the playlist, and maintain a list of recently played songs.

Features
Add a New Song: Add a song to the playlist, either from user input or a file.
Delete a Song: Remove a song from the playlist by name or position.
Display Playlist: Display all songs currently in the playlist.
Total Songs: Count and display the total number of songs in the playlist.
Search for a Song: Search for a specific song in the playlist by name.
Play a Song: Play a song, which adds it to the recently played list.
Recently Played Songs: Display a list of songs that have recently been played.
Sort Playlist: Sort the playlist alphabetically.
Add Songs from File: Add songs to the playlist by reading them from a file.
Technologies Used
C++: The program is implemented in C++ using standard libraries.
Data Structures:
Doubly Linked List: Used to store the playlist and manage songs efficiently.
Vectors: Used to maintain the recently played list and for sorting the playlist.
Data Structures and Algorithms (DSA) Concepts
The project demonstrates the following DSA concepts:

Doubly Linked List: This is used to represent the playlist. Each node contains a song and pointers to the previous and next nodes for efficient insertion and deletion operations.
File Handling: The playlist is stored in a text file (playlist.txt) and songs are added or removed based on user interaction. This demonstrates basic file handling in C++.
Sorting: The playlist can be sorted alphabetically using vectors to store song names, which are then used to rebuild the sorted list.
