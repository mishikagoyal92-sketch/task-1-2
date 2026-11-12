# Task 1 (2)

I have already built this AI Recommendation Engine project. Do NOT rebuild it from scratch or remove any existing working features.



First, inspect the entire existing codebase and compare it against the following missing requirements. Then implement them properly while preserving the existing Next.js frontend, Express backend, MongoDB database and Groq AI integration.



1. Feedback-based recommendations



- Allow users to like and dislike recommended movies.

- Store feedback in MongoDB, linked to the user profile and movie.

- Use this feedback to influence future recommendation results.

- Ensure feedback actually changes recommendation ranking.



2. Kids' content restrictions



- Implement strict maturity-rating restrictions for Kids profiles.

- Filter out unsuitable movies before sending recommendations to the frontend.

- Enforce restrictions on the backend, not just through UI filtering.

- Ensure AI-generated recommendations cannot bypass these restrictions.



3. Recommendation caching



- Implement caching for recommendation results.

- Cache results based on user profile, preferences and relevant feedback.

- Invalidate or refresh cached results when preferences or feedback change.

- Avoid unnecessary repeated Groq API calls.



4. Pagination



- Add backend pagination for movie listings and recommendation results.

- Support page number and page size parameters.

- Return total results, current page and total pages.

- Connect pagination properly to the frontend.



Important instructions:



- Do not create dummy buttons or non-functional features.

- Implement actual frontend, backend, API and MongoDB functionality.

- Do not replace existing working functionality with mock data.

- Do not leave TODOs or unfinished placeholders for these requirements.

- Maintain the existing design and responsiveness.

- Add or update necessary database models, API routes and validation.

- Update README.md with setup instructions and the newly implemented features.

- Run available checks and fix errors.



Before finishing, provide a clear checklist showing which requirements are implemented and which could not be verified. Do not claim a feature works unless you have actually implemented it.

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/776c4fcb-731a-4fe7-a48f-49dcf65718db).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
