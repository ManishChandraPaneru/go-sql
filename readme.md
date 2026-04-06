bookstore-route.go(where user will hit)->app.go(where we will connect to mysql database)->utils.go->main.go->model.go->book-controller.go


The users interact with the routes, routes send control to the controllers where we have all our logic controllers then have to perform some operations with the database. The database have to reside inside our models file(book.go).