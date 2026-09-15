# **Simple Line Editor — Help**

## **1. Overview**

Simple Line Editor is a C program that allows the user to edit a document line by line.

It has four options:

1. Insert line
2. Delete line
3. Display document
4. Exit

## **2. Main Menu**

SIMPLE LINE EDITOR


1. Insert line
2. Delete line
3. Display document
4. Exit


Enter a number to select an option.

## **3. Insert Line**

Select `1` to add a new line.

Enter the line number and text.


Enter your choice: 1
Enter line number: 1
Enter text: Hello World
Line inserted successfully.


## **4. Delete Line**

Select `2` to delete a line.

Enter the line number.


Enter your choice: 2
Enter line number to delete: 1
Line deleted successfully.


## **5. Display Document**

Select `3` to see all the lines.


----- DOCUMENT -----
1. Hello World
2. Welcome to C
--------------------


If there are no lines:


Document is empty.


## **6. Exit**

Select `4` to close the program.


Enter your choice: 4
Exiting editor...


## **7. Error Handling**

The program shows an error when:

* The line number is invalid.
* The document is full.
* The document is empty.
* The choice is invalid.
* Memory cannot be allocated.

## **8. Data Structure**

char *lines[MAX_LINES];


The program can store up to 100 lines.

Memory is allocated using malloc() and released using free().

End of Help
