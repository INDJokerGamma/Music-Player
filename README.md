
##Playlist Manager
This project is a C++ application for managing and interacting with a playlist. It provides functionalities such as adding, deleting, searching, and playing songs, along with maintaining a record of recently played tracks. The program also supports saving and loading playlists from a file.

#Features
Add Songs: Add new songs to the playlist manually or from a file.
Delete Songs: Remove songs by name or position.
Search Songs: Search for specific songs in the playlist.
Play Songs: Select and play songs, updating the recently played list.
Recent Tracks: View the list of recently played songs.
File Support: Save and load playlists to/from a text file.
Playlist Statistics: Count the total number of songs in the playlist.

#Requirements
C++ Compiler (e.g., GCC)
Basic knowledge of file handling in C++

#Data Structures Used
Doubly Linked List:
The playlist is implemented using a doubly linked list. Each song is stored as a node containing the song name, with links to the previous and next nodes, allowing efficient traversal and modification of the playlist.
Stack:
A stack is used to maintain the list of recently played songs. This ensures that the last played song is easily accessible, enabling quick retrieval for the "recently played" and "last played" functionalities.

#Usage
Clone the repository and compile the code using your preferred C++ compiler.
Follow the menu-driven interface to interact with the playlist:
Add songs
Delete songs
Search for songs
Play songs and manage the playlist

#Notes
Use underscores (_) instead of spaces in song names.
The playlist is saved in playlist.txt for persistence across sessions.
