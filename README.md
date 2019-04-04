##graphl-user
This is a just sample demo for graphql simple use. I copy other people's code and you can use this to get a feeling about what graphql is.

Two point: 
1. We use json-server to provide mock data which graphql can use. Use url http://localhost:3000/users, you can get the mock data below.
{
  "users": [
    {
      "id": "23",
      "firstName": "EditPatch",
      "age": 23,
      "companyId": "1"
    },
    {
      "id": "40",
      "firstName": "Nick",
      "age": 34,
      "companyId": "2"
    },
    {
      "firstName": "Stephen",
      "age": 26,
      "id": "8SKrSYp"
    }
  ],
  "companies": [
    {
      "id": "1",
      "name": "Apple",
      "description": "iphone"
    },
    {
      "id": "2",
      "name": "Google",
      "description": "search"
    }
  ]
}
2. Use the url http://localhost:4000/graphql to try your graphql at local.
