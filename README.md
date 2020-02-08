# learning-graphql
1. CRUD resources
1. 權限認證
1. Versioning
1. Validation
1. Error handling
1. 

# why we are using graphql



# install
1. npm install
1. node server.js
1. browser to http://localhost:4000/graphql

# query example
```
{
  getDie(numSides: 1) {
    numSides
  }
  usersList(opts: {page: 2, pageSize: 30}) {
    meta {
			page
      pageSize
    }
    users {
      id
      age
      name
      count
      height
      notes {
        id
        data
      }
    }
  }
}
```


