# Character Query using GraphQL

This project retrieves character information from the **Rick and Morty GraphQL API** using their ID.

## Endpoint


## Objective
To write a GraphQL query using the `character(id: ID!)` field to fetch:
- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

## Example Usage
Run the query in a GraphQL client such as Apollo Studio, Insomnia, or Postman.

Example:
```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
