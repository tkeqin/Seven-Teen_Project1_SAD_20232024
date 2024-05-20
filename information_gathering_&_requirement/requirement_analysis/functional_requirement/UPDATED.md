## Functional Requirements (Process, Input, Output)

### Processes for login
| Process           | Input                 | Output                     |
|-------------------|-----------------------|----------------------------|
|  Login (Student)  | Student ID Password   | Student server main menu   |
| Login (Librarian) | Librarian ID Password | Librarian server main menu |

### Process for book search
| Process             | Input                                   | Output                            |
|---------------------|-----------------------------------------|-----------------------------------|
| Search book         | Book title                              | Search result (book listing)      |
| Choose desired book | Desired book option (from book listing) | Shelving location |

### Process for creating book request
| Process             | Input                                                                                         | Output                            |
|---------------------|-----------------------------------------------------------------------------------------------|-----------------------------------|
| Borrow book         | Book ID, student ID                                                                           | Due date slip                     |

### Process for book record addition
| Process             | Input                                   | Output                            |
|---------------------|-----------------------------------------|-----------------------------------|
| Add book record     | Book ID, Book title, Author, Publication date, Subject, Description | New book record                   |

### Process for book record update
| Process             | Input                                   | Output                            |
|---------------------|-----------------------------------------|-----------------------------------|
| Update book record  | Book ID Detail to be updated (book ID/book title/author/publication date/subject/description) | Existing book record              |

### Process for book record deletion
| Process             | Input                                   | Output                            |
|---------------------|-----------------------------------------|-----------------------------------|
| Delete book record  | Book ID                                 | -                                 |

### Process for issuing book request
| Process                      | Input                                                                                         | Output                            |
|------------------------------|-----------------------------------------------------------------------------------------------|-----------------------------------|
| Issue student’s book request | Book ID, student ID                                                                           | Due date slip                     |
