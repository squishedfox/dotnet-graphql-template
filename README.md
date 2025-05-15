# dotnet-graphql-template

## Summary

Template for making new GraphQL Microservice Endpoints

## How to Use

1. Find and replace the `dotnet-graphql-template` with your `<project-name>`
2. Run `dotnet restore` to make sure all your packages download correctly
3. Delete this section when you are done

## Development

1. Start Docker Desktop or at least your docker machine engine
2. Run `docker compose up -d` to start mongodb database and the viewable server
3. Run `cURL http://localhost:8080` and validate you receive an HTTP Status 200 OK
3. Go to http://localhost:8080/graphql in your browser

## See Also

- [MongoDB Driver](https://www.nuget.org/packages/MongoDB.Driver)
- [GraphQL DotNet](https://graphql-dotnet.github.io/docs/getting-started/introduction/)