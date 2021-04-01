## GraphQL API for Authors and Books

In about 100 lines, we are able to fit our entire application code for a simple author and book API.

On the client side, we can query exactly the data that we want to. You can query for the author, their ID name, and all the books in their name in one single query. So the information sent to the client is smaller and much more specific, making it easier to work with because you don't have to create a bunch of custom endpoints every time you want to get a different set of data back. You just tell the server you want different data, and it will give it to you. It's smart enough to do that.

You can do everything from creating, reading, updating, deleting data much faster than a REST API could.
