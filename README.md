# tours-management-mongoose

Tour Management System

You are required to build an API for a tour management system for this assignment. In this system, you have to provide several endpoints to the client. The endpoints are:

`ROOT ROUTE :`
[https://tours-management.vercel.app/api/](https://tours-management.vercel.app/api/tours)

- `GET /tours`

1. Get all the tours
2. The client can select some specific fields for getting the information he needs as query.
3. `Example:` /tours?fields=name,image
4. Must be paginated.
5. (BONUS) The client can send a field (e.g. price) as query to sort the data with it.
   Example: /tours?sort=price

- `POST /tours`

1. Add a tour
2. Must have a schema and the body should be validated through it.

- `GET /tours/:id`

1. Get a tour details by id
2. end all the information of the tour
3. Increase the view count by 1 for this tour every time a user hits this endpoint.

- `PATCH /tour/:id`

1. Update a tour
2. (BONUS) Body should be validated

- `GET /tour/trending`

1. Get top 3 viewed tour

- `GET /tour/cheapest`

1. Get top 3 cheapest tours
