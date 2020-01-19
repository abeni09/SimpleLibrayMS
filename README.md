# README
# A simple web-based library management system and a covering report

The local library currently operates using a paper card system. Each book that the library stocks has an associated paper card inside it. When library users wish to borrow a book, they give the paper card to the librarian, who will file the card away in a drawer. When the book is returned, the card is retrieved from the drawer and placed inside the book before the book is returned to the shelf.
This system is inadequate for several reasons. Library users cannot check themselves whether a book is available or not – they must ask the librarian, who will check the drawer to see if the book’s card is there or not. This process takes time, is prone to error (the librarian might “miss” the card when checking the drawer or the card may actually go missing) and can only take place during the library’s opening hours.
The librarian also only has quick access to the books currently on loan – there is no list of books that are available for borrowing. The library stores around 10,000 books – keeping track of all of them is extremely difficult without a computerised system. The library has recently bought several computers for use by the librarian and library users, which have been set up to only allow web browsing. A separate computer has also been purchased, which may be used as a server.
The main objective of this assignment is to develop an easy-to-use online library records management system to replace the paper card system. This new system must cater for both the librarian and library users, and should be accessible to library users outside of the library at any time via a web browser. The librarian will need to be able to manage book records whilst library users should be able to browse them. Therefore, different interfaces are needed for the librarian and library users. Due to the number of books the library stores, a search function for both interfaces would be extremely beneficial.
There is plenty of scope to enhance the usability of the system. You may wish to explore and implement other functions such as reserving books.           


General specification:
The application must be implemented on the Ruby on Rails framework, using Ruby version 2.x and Rails version 5.x.
 
Basic requirements:
•	Data entry: Each record must consist of at least 4 data fields, including book title, author(s), ISBN and Publisher. Other relevant fields may also be implemented.

•	Data processing: The information of each record should be stored in a simple database that you will need to design and implement.

•	User interface: Buttons, textboxes and other inputs, controls and graphics should be provided to initiate various system functions.

•	Security: The application should be secured by allowing only permitted users (i.e. the librarian only, not public library users) to edit the records.

•	Data display:
o	For the librarian – a display containing a web form for allowing data entry. This should allow the librarian to manage borrowing and returning of books

o	For library users - a general “higher-level” display for showing a list of currently available books. The list should be limited to 5 records per page, ordered alphabetically by title.

Desirable requirements:

•	Search function: search by title, author, or ISBN.

•	Search results: the system should display the results and the details of an associated record accordingly.

•	Provide an interface to display all the details of a particular record.

•	Provide an advanced search function to allow searching by a combination of title, author, and/or ISBN, and display the results.

•	Provide a means to enable reserving and returning of books.



