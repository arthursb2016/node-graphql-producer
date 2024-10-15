# node-graphql-producer
Node GraphQL producer example

> GraphQL is a query language for APIs and a runtime for executing those queries by using a type system you define for your data. It was developed by Facebook in 2012 and publicly released in 2015. It provides a more efficient, powerful, and flexible alternative to REST for fetching and modifying data from an API.
>
> Key features of GraphQL:
>
> Single Endpoint: Unlike REST, which typically requires multiple endpoints for different types of data, GraphQL exposes a single endpoint where the client defines the structure of the response.
>
>Declarative Data Fetching: Clients specify what data they need, avoiding over-fetching (retrieving more data than necessary) or under-fetching (requiring multiple requests to retrieve the required data).
>
> Strongly Typed Schema: GraphQL uses a type system to define the shape of the API. The schema defines the types and relationships between data, ensuring that API operations conform to the predefined structure.
> 
> Real-time Data with Subscriptions: In addition to queries (for data retrieval) and mutations (for modifying data), GraphQL supports subscriptions, which enable real-time data updates.
>
>Introspection: GraphQL APIs are self-documenting. Clients can query the schema itself to discover available data and types, making it easier to understand and use the API.
>
>Versionless API: Since the client defines the structure of the response, GraphQL reduces the need for versioning, as new fields can be added to the schema without affecting existing queries.

Consumer example at:
https://github.com/arthursb2016/node-graphql-consumer