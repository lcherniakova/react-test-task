# react-test-task

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


