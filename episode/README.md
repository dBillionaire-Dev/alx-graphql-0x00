# GraphQL Episode Query

This project contains a simple GraphQL query to retrieve details of a specific episode.

## Example Query

```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
