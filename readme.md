# Codeigniter 3 Assessment


These assessments questions is designed to evaluate developer's understanding on the framework. To answer the questions, you may fork this repo and answer it in this codeigniter installation.

#### Question 1
Explain how to create a static page with the given uri `http://{domain}/page/about`.


#### Question 2
From solution no 1, explain how to change the uri to `http://{domain}/about`.


#### Question 3
Given that you have a database schema as below: 
```mysql 
  CREATE TABLE news (
        id int(11) NOT NULL AUTO_INCREMENT,
        title varchar(128) NOT NULL,
        slug varchar(128) NOT NULL,
        text text NOT NULL,
        PRIMARY KEY (id),
        KEY slug (slug)
);
```

Explain how would you query a record and display it to the user when visiting the uri `http://{domain}/news/{slug}` where slug is equivalent to the `slug` column in the table.


#### Question 4
How can you prevent sql injection when providing for the solution in question 3.


#### Question 5
Explain how to create a page where user can create a news entry into the database.

#### Question 6
Explain how can you validate input from user in question 5.

#### Question 7
Explain how can you save a user session when a user has logged in and how to retrieve the session.

#### Question 8
Show how can you prevent file upload with size not more than 2MB and only to accept `pdf` file.

#### Question 9
Based on the schema in question 3, show how you write a migration class to create the table using codeigniter.

#### Question 10
What do you think of codeigniter compared to other PHP frameworks available e.g Laravel, Symfony, CakePHP