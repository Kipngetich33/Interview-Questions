
## 1.What is Python ?
Python is a general purpose high level programing language that was built in such a way as to allow better code readability and a simpler syntax that allows programmers to express ideas in fewer lines of code.

## 2.In what areas can we use python programing language?
* Web Development 
* Data Analyis 
* Game development 
* Machine learning
* Used in education for teaching programing concepts
* Developing desktop Gui application
* Software Developement
* ERP systems development

## 3.What is the disadvantage of using Python compared to other compiled languages like Java?
python runs with the help of an interpreter rather than a compiller for that reason it is generally slower than compilled languages such as java.

## 4.Define a Python module, script and package.
* python module - is any python file that can expose its such things as classes and functions outside itself making it possible to import them and use them in other modules

* python script - is an executable piece of code in python which can run without the importation of any external dependicies

* package - this is a collection python modules with the __init__ .py module within it making it possible to easily import and uses the moduels outiside the package

## 5.What is the difference in using Python 2+ and Python 3+?

Python 3 is the current version of the python language and with very subtle differences with python 2. The main difference between the two however is the print statement; python 2 does not require the use of parenthesis around the parameter which is not the case for python 3.

## 6.Name the top 3 programmer caused Python errors.
* Indentention errors
* Creating circular dependencies
* VAriable names that clash with python standard library names

## 7.What is the difference between a list and a tuple ?
A list is mutable while a tuple is not

## 8.What is a set?
A data stuctures that contains immutable collection of items the set itself is however mutable

## 9.Name the various data types in Python
* Integer
* Float
* String 
* Boolean
* 

## 10. What is a decorator?
A funtion that provides a simple way of calling higher order function within another function without having to modify the later

## 11. Define pypi?
Pypi(python package index ) is the repository that contains all the python software used by the python community. Software from this repository of software are easily installed using the pip command

## 12. What is the difference between Python built in modules and external modules?
Python built in modules refers to all the modules found in the python standard library

## 13. What is flask?
Flask is a micro- web framework that is built using python, flask uses Jinja for templating and also the Werkzeug toolkit 

## 14. How does flask differ from other frameworks?
* Flask is less oppionionated, it gives the developer the bare minimum and allows them to choose on more add ons
* For that reason flask is more flexible as compared to other frameworks like django
* It does not have an obvious way of doing things, it is therefore better for the purposes of learing things every twist becomes a new learning expirience

## 15. What comes built in in flask?
* Jinja 
* Werkzeug toolkit 

## 16.What is a virtual environment and why is it useful?
Is an isolated environment that allows the developers to install libraries and dependacies when building an app without affecting global software and libraries

## 17. What is a template?
IS a flask file structured using HTML,CSS, Bootstrap etc. that has placeholders that displays the actual data on the site

## 18. What is a view function?
Is a fuction that returns a html template and data relating to that page

## 19. Define a http request?
A request that fetches a file or data from a web server

## 20. What is a flask extension?
These refer to extra support features available for a flask app for example the database support extension that allows the app to communicate with the database

## 21. What is a Model ?
A model is a python class that defines how blueprint of a database objects 

## 22. What is an ORM and how does it differ from conventional ways of interacting with a database?

## 23. What is needed to connect to SQLALCHEMY?
a database specific driver for example for the postgress database the psycopg2 driver connects the flask app to the database

## 24. What is an application factory?
Refers to the app module where the app all the app dependancies are imported and the app instance is generated

## 25. What is a blueprint?
A blueprint is a divisional structure more or less the same as the app but unlike the app Blueprints however have to be registered in the main app __inti__.py module

## 26.How can you connect a blueprint to an application factory?
By registering the blueprint in the application factory

## 27. What is a migration file?
is a files that stores the changes in the database format as dictated by the modified module classes 

## 28. Why are migration files useful?
Migration files stores changes to the database structure in each case and hence can allows the developer to revert back to the previous format of the database.

## 29. Why do we use flask-script in our application?
It provides support for writting external scripts in the app such as the shell

## 30. Explain the http request response cycle when a person visits a url.

## 31. State 4 types of responses that can be returned by a view function.

## 32. What is the purpose of the url_for function?
creates a path to static files within the flask application

## 33. What is the purpose of a requirements.txt file?
It lists down all the dependancies that the app needs in order to run effectively. This is useful especially when deploying to servers like heroku as it tells the server which dependancies it will need to install to allow the app to run

## 34. What are app configurations?
These are key value pairs stored in the config.py of out app and simply presets the the app for the users

## 35. How are different kind of variables defined in Jinja2 templates ?

## 36.What are macros? 
These are templates that are used to store loops that can then be easily be inherited and applied in other templates

## 37. Define template Inheritance.
Refers to extending one template in another template which gets rid of the need to repetitively create similar code in many templates. 

## 38. What are blocks in Jinja templates ?
These are section of templates that hold specific contents of that page some examples include the block content block and the include block

## 39. How are templates reused in Jinja2 ?
Templates are re-used in jinja by simply extending the template in another template

## 40. What are variable filters ?
Filters are special built-in methods or user defined functions in flask that gives an out of the box functionality for manipulating data.The tojson() filter in flask for example allows the user to easily convert data into json file by just using {{data | tojson}}

## 41. How are static files stored in a flask application ?
static files are stored within the static folder and accessed with the help of the url for

## 42. How is authentication managed in a flask application ?
It is managed with the help of flask-login extensions that has an out of the box functionality that allows for the creation of users as well as management of login sessions

## 43. What are database sessions ?
These are temporary context created upon request by and app or user to facilitate the interaction with the database. It therefore allows for the safe CRUD application on database objects

## 44. Describe one-many database relationships.
When elements of a table1 can reference various elements of another table2 the table can be said to have a many to one relationship with table 2.

## 45. How do you create a one-many database relationship with SQLAlchemy?
By abstrating with the help of data models to define the foreign key column and the relationship column in the other column

## 46. What is a foreign key?
It is a column in one table that is used to refence another table in the database

## 47. What is the difference between a SQL database and a Nosql database?
SQL implements a relational database model while Nosql implements a  none relational database model.

## 48. What is the difference between a GET and POST request?
GET requests are basically used to retrive data from specified sources they are however less secure and their use should therefore be used carefully, POST on the other hand is used to update or create new resources in a target resource

## 49. What is CSRF and why do we need to protect our applications from it?
CSFR is the abbreviation for Cross Site Request Forgery and is s type of attack that exploits the trust that a site has on a users browser.
CSRF attacks can be prevented through two main ways:
1. Unsure that your application uses a CSRF key
2. Minimize on GET methods and instead use POST

## 50. What is a status code and what do the various status codes mean?
These are shortcodes for http requests that define the state of the current request. Some of the status codes are as follows:
404- page not found
200 - request processed successul
501 - internal server error

#### 100's
This are informational codes often telling the user that the request has been recieved and is awaiting processing

#### 200' 
These are codes that tells the user that the request was recieved and accepted

### 300's 

### 400's 

### 500's 


* 300' 
* 400's codes represent errors
* 500's codes rep

