This project is a Library Management System built using JSP, Servlets, and JDBC.

It allows the administrator to add, view, and manage books and authors in the library.

The project follows a proper MVC architecture, separating Beans, DAO layer, Service layer, and Servlets.

The Bean classes (AuthorBean, BookBean) store the data models used throughout the application.

The DAO layer (AuthorDAO, BookDAO) handles all database-related operations such as inserting and retrieving records.

The Service layer provides an intermediate layer for performing business logic and communicating between servlets and DAOs.

The Servlets (MainServlet, ViewServlet) process user requests, interact with services, and forward responses to JSP pages.

The project uses MySQL for storing author and book details, and DBUtil manages database connections.

It includes basic features such as adding authors, registering books, and viewing all stored records.

This project demonstrates essential Java web development concepts like CRUD operations, JSP form handling, Servlet routing, and database connectivity.

<img width="402" height="320" alt="image" src="https://github.com/user-attachments/assets/aca4af4d-21d7-4ada-ba55-58aa1721427a" />
<img width="375" height="208" alt="image" src="https://github.com/user-attachments/assets/15ba7cdd-703a-42d3-99dd-d337f3a4b3b2" />
<img width="359" height="251" alt="image" src="https://github.com/user-attachments/assets/629b3424-6371-4401-a5d2-db091080dcc6" />


