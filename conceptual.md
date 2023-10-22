### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

  PostgreSQL is an open-source relational database management system used for storing and managing data.

- What is the difference between SQL and PostgreSQL?

  SQL is a language used to interact with databases, Postgres is an ORDBMS that uses SQL as its query language

- In `psql`, how do you connect to a database?

  psql {database name}
  or if you are already in psql:
  \c {database name}

- What is the difference between `HAVING` and `WHERE`?

  The WHERE clause filters rows before they are grouped, while the HAVING clause filters grouped or aggregated results after grouping has occurred in SQL queries.

- What is the difference between an `INNER` and `OUTER` join?

  An INNER JOIN retrieves matching rows from both tables involved in the join, while an OUTER JOIN retrieves matching rows and non-matching rows from one or both tables.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

  A LEFT OUTER JOIN retrieves all rows from the left table and matching rows from the right table, while a RIGHT OUTER JOIN retrieves all rows from the right table and matching rows from the left table in SQL.

- What is an ORM? What do they do?

  Object-Relational Mapping is a programming technique that allows developers to interact with relational databases using object-oriented programming languages

- What are some differences between making HTTP requests using AJAX
  and from the server side using a library like `requests`?

  AJAX allows making asynchronous requests directly from a web page to a server without refreshing the page, while requests is used in server code to send HTTP requests and process responses.

- What is CSRF? What is the purpose of the CSRF token?

  Cross-Site Request Forgery is a type of web security vulnerability, and the purpose of a CSRF token is to prevent unauthorized actions by ensuring that a request to a web application is made only by an authenticated and authorized user.

- What is the purpose of `form.hidden_tag()`?

  to render hidden input fields in an HTML form, used for CSRF protection that needs to be sent back to the server when the form is submitted.
