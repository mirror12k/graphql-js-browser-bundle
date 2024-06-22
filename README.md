# GraphQL.js Browser Bundle

This repository is a mirror of [graphql/graphql-js](https://github.com/graphql/graphql-js) created for the exclusive purpose of generating a browser build of the JavaScript file.

## About

GraphQL.js is the JavaScript reference implementation for GraphQL, a query language for APIs created by Facebook. This mirror repository automates the process of creating a single-file browser build of GraphQL.js, which can be downloaded from the [Releases](https://github.com/mirror12k/graphql-js-browser-bundle/releases) section.

## Usage

You can find the js bundle for browsers in the [Releases](https://github.com/mirror12k/graphql-js-browser-bundle/releases).
Import with
```html
<script src="graphql.bundle.js"></script>
```

Use in code as follows:
```javascript
// Define GraphQL schema
const { graphql, graphqlSync, buildSchema, GraphQLSchema, GraphQLObjectType, GraphQLString } = window.graphql;
const schema = buildSchema(`
  type Query {
    self: Float
  }
`);
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Security

If you discover any security issues, please report them to the original [graphql/graphql-js](https://github.com/graphql/graphql-js) repository.

## Credits

All credits for the original implementation go to the contributors of the [graphql/graphql-js](https://github.com/graphql/graphql-js) repository.
