![Nirav Patel](https://cdn.fs.teachablecdn.com/mCT5A6Z1ReeavARaYGRD)

# GitHub Based JSON data server 

Use json data files for mimicking a backend server. This data can be served to a front-end application, which can use it to render its UI. The goal of the is to create a temporary datastore that can be directly used for a front end application. 

Each json file in the repository is an end point. The relative path of the json file acts like an end point for an api call. The base url for api calls is 

    https://niravkpatel28.github.io/json-data-server/
    
To fetch data simply append the base url with the relative path of json file. Example to fetch blogs end point is 

    /blogs/blogs.json

# Advantages 
This repository is a simple tool for anyone who wants to test out a front end feature with static data. To add an end point simply add the relevant json data into the root folder or by creating a directory with the json data. It can be nested to support different versions of same resource. The api end point is the relative path. 

# Api End Points
[/blogs/blogs.json](https://niravkpatel28.github.io/json-data-server/blogs/blogs.json)

[/books/books.json](https://niravkpatel28.github.io/json-data-server/books/books.json)

[/books/categories.json](https://niravkpatel28.github.io/json-data-server/books/categories.json)

[/companies/companies.json](https://niravkpatel28.github.io/json-data-server/companies/companies.json)

[/employees/employees.json](https://niravkpatel28.github.io/json-data-server/employees/employees.json)

# Limitations
The basic limitation of this repository is that it is serving static data. It cannot be used to serve api calls with route parameters or query parameters. The end user will simply receive entire json data which has to be parsed and used for application UI. 
For having a backend server that is based on json server which supports query parameter and router parameters use the node package [json-server](https://www.npmjs.com/package/json-server).

***Use the [link](https://github.com/niravkpatel28/heroku-json-data-server) for an api backend server that supports route parameters and query based filtering.***
