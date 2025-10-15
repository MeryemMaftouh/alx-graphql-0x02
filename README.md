# Query the GraphQL

## Objective

This project demonstrates how to query the Rick and Morty GraphQL API to fetch and display episode data in a Next.js application.

## Implementation

- TypeScript interfaces (`EpisodeProps`, `InfoProps`, `EpisodeCardProps`) define the structure of episodes and pagination info.
- `GET_EPISODES` query fetches episodes with `id`, `name`, `air_date`, and `episode`.
- `useQuery` from Apollo Client is used in `pages/index.tsx` to fetch data and handle loading/error states.
- Each episode is displayed via the reusable `EpisodeCard` component.
- Pagination uses the `info` object from the query to navigate pages.

## Outcome

Provides a typed, modular, and responsive way to display GraphQL data with pagination in a React/Next.js app.
=======
# alx-graphql-0x02
>>>>>>> ff1ea483f27a36e81049b9460141852191baf287
