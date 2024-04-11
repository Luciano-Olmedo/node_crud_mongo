
# Basic Crud

Simple CRUD with the most common actions such as read, create, delete and delete.

Routes:

getBooks:

https://nodecrudmongo-production-ef3a.up.railway.app/books

postBooks:

https://nodecrudmongo-production-ef3a.up.railway.app/books

body
{
	"title": "title",
	"author": "author",
	"genre": "genre",
	"publication_date": "1900"
}

put:
https://nodecrudmongo-production-ef3a.up.railway.app/books/:id  


example:https://nodecrudmongo-production-ef3a.up.railway.app/books/66144fbb74df369338229e82

body
{
	"title": "title",
	"author": "author",
	"genre": "genre",
	"publication_date": "1900"
}

patch:
https://nodecrudmongo-production-ef3a.up.railway.app/books/:id  

example:
https://nodecrudmongo-production-ef3a.up.railway.app/books/66144fbb74df369338229e82

{
    "title":"title",
    "genre" : "genre"

}

Delete:
https://nodecrudmongo-production-ef3a.up.railway.app/books/:id

example:

https://nodecrudmongo-production-ef3a.up.railway.app/books/6614504674df369338229e88
