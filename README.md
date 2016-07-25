# graphql-server
GraphQL Server. Demo project.

## What's it?
It is GraphQL server that uses a SQL, MongoDB and REST.
To run it locally you need:
1. Run `npm install`
2. MongoDB installed and configured on your machine.
3. Run `npm start`

Now you can execute queries like this:
```
{
  author(firstName: "Edmond", lastName: "Jones") {
    firstName
    lastName
    posts {
      title
      views
    }
  }
  getFortuneCookie
}

```
