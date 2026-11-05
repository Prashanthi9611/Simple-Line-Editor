
# Simple Line Editor - Help Guide

## Description
A command-line text editor developed using C.
It allows users to create, modify, search and save
text documents.

## Commands

### 1. Insert Line
Adds a new line at a specified position.
Example:
Enter choice: 1
Enter line number: 2
Enter text: Welcome to C

### 2. Delete Line
Deletes a line using its line number.
Example:
Enter choice: 2
Enter line number: 1

### 3. Edit Line
Modifies an existing line.
Example:
Enter choice: 3
Enter line number: 1
Enter new text: Hello World

### 4. Display Document
Displays all lines with line numbers.
Example:
Enter choice: 4

### 5. Save File
Saves the document into a text file.
Example:
Enter choice: 5
Enter filename: notes.txt

### 6. Load File
Loads a previously saved text file.
Example:
Enter choice: 6
Enter filename: notes.txt

### 7. Search Word
Searches for a word or phrase and displays
the matching line numbers.
Example:
Enter choice: 7
Enter word: Hello

### 8. Find and Replace
Replaces matching text in one line or
throughout the document.
Example:
Find: Hello
Replace: Hi

### 9. Undo Last Action
Restores the document to its state before
the most recent modification.
Example:
Enter choice: 9

### 10. Line Count / Word Count
Displays the total number of lines and words.
Example:
Enter choice: 10

### 0. Exit
Exits the editor and releases allocated memory.

## Compilation
gcc -std=c11 -Wall -Wextra main.c -o editor

## Execution
./editor
