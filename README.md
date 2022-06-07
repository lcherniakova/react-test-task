# react-test-task -Front-end 

## Task:
1. Create a reactjs application which is capable to render nested json data struture of the following format:
```js
{
  "data": [
    {
      "name": "String",
      "children": [
        {
          "name": "String",
          "children": [
            // ...
          ]
        }, {
          "name": "String",
          "children": [
            // ...
          ]
        },
        // ...
      ]
    }, {
      "name": "String",
      "children": [
        // ...
      ]
    },
    // ...
  ]
}
```
This component should show each node's name and indicate relation to it's children nodes. Example:
![Component example](https://raw.githubusercontent.com/AlpacaGoesCrazy/react-test-project/master/example.png)

2. Make each node show/hide all nested components by click on it's name.
3. Make collapsible component logic from step 2 reusable between different components by using react hooks or HOC.
4. Using react context make it so when you click on any last node it will close all nodes in the tree (showing only continent list).
5. Connect [this countries graphql API](https://countries.trevorblades.com) to your components to display nesting of `Continent`, `Country` and `Language` types


Graphql-backend-test-task

Task:
1. Create a nodejs graphql server with a query to fetch a list of commits from facebook/react repository using github rest api as a data source. Commit list should provide minimal information including sha, message, html url, commiter info, date.
2. Add pagination to query for listing commits
3. Protect your graphql server using api key authorization. Store your api keys using an ORM and sqlite inmemory database.
4. Add a mutation to generate new api key.
5. Add a query for displaying ‘Hello World’. Make this (only this one) operation accessible without authorization.


