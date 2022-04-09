# Spring boot application using GraphQL

In this project I created a model called book and then created a JPA repository (which acts as a storage for collection of objects).
Later, created a book resource where we are using graphql service. 
Inside graphql service class we are loading graphql schema which contains the query type to query the database into graphql API
To load the schema we can wire it in runtime using runtime wiring which was provided by graphQL API.
I have loaded the data into HSql and injected into repository and used data fetchers to fetch the data
