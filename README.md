# ISBN reader app

The ISBN reader App is an android application designed with App inventor aiming to streamline the making of a personal library.
The library is stored within a Google Sheet and Google Apps Script (GAS) is used as a server by the App.


# Basic function of the App

The android app is using built-in camera to read books barcode and extract EAN / ISBN number. The ISBN number is transmitted to the GAS server. 
The server is looking on several providers website for information on the book.
The book is saved in a google sheet with the following information: ISBN, Title, Author, Description, Cover Front & Back, number of pages.



# Work in progress

I have a stable 0.2 version which is working as of today but lacks key components to be fully called a full version.

Most notable:
_ Streamline the search experience and combine data from multiple vendors
_ Access library from the app
_ Initialize settings to allow easy set-up of the GAS server and communication with the app.
