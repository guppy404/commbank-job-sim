# CommBank Forage Job Simulation

Forage Commonwealth Bank Software Engineering Job Simulation: feature extension for a fullstack web app, focusing on goal personalisation, REST API integration, database persistence, and unit testing.

## Tech Stack

**Frontend:** React, TypeScript, Redux, styled-components, emoji-mart  
**Backend:** C#, ASP.NET Core (.NET 6), MongoDB Atlas  
**Testing & Tools:** xUnit, Postman, Coverlet, Git, GitHub

## Features Implemented

- **Goal Personalisation:** Added emoji icon support across frontend and backend models, including an interactive emoji picker and updated goal cards.
- **API & Database Integration:** Integrated React/Redux state updates with ASP.NET Core REST endpoints and MongoDB Atlas for persistent goal customisations.
- **Unit Testing:** Implemented xUnit tests for the `GetForUser` controller endpoint using fake services, achieving full coverage of the targeted method.

## Repository Structure

- `frontend/` — React/TypeScript application
- `backend/` — ASP.NET Core API and xUnit tests

## Development Workflow

Implemented and tested changes across two independently forked repositories, using feature branches and GitHub pull requests.

**Original Pull Requests:**
- Backend: https://github.com/fencer-so/CommBank-Server/pull/409
- Frontend: https://github.com/fencer-so/CommBank-Web/pull/291

## Acknowledgements

Developed as part of the Commonwealth Bank Software Engineering Job Simulation, extending provided starter code. This repository showcases my contributions and is not an official Commonwealth Bank product.
