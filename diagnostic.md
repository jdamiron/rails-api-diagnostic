# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
// To store and save data, and also to manage requests between
the browser and server.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
Model
```

Which layer in the MVC pattern communicates with the model?

```bash
The controller, it also communicates with the database.
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
Views aren''t needed when working with single page web apps, views are
used when working with multi-page web apps, which is considered old fashioned.
```

What does C.R.U.D stand for?

```bash
Create
Read
Update
Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
Controllers
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
The browser sends the request to the server. The server communicates with the
person controller and asks to retrieve item 1. The person controller then
communicates with the person modal and sends it the request. The modal searches
through the database to supply that information, if it is available, and sends
the information back to the controller. The controller then sends the request
to the server and from the server to the back to the browser/client.
```

What is the command to generate a new rails-api app?

```bash
rails new appname
```

What is the command to start an instance of a rails server?

```bash
rails s or rails server
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
bundle exec rake db:create
bundle exec rake db:drop
bundle exec rake db:migrate
```

What is the command to scaffold a pet with a name and an age?

```bash
rails generate scaffold pet name:sparky age:3
```

List two advantages of using serializers? (2 bullet points)

```bash
Gives each object in the table a unique identifier and it also increments for
us.
```
  #statements
done
```
