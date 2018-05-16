# graphql-integration

npm install
npm start


RUN LINK: http://localhost:3000/graphql

Query
```
query{
  author(id: 2243) {
    name,
    books {
      title,
      isbn
    }
  }
}
```
