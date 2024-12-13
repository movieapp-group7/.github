# MovieLog (Group 7)

## Project description

MovieLog is a web platform for social and entertainment movie data tracking. Users can save
their favorite movies and TV-shows, being able to keep their favourite lists either private or
shared publicly via url. Users are able to have social interaction via group pages and writing
reviews. Data from users, their favourites, reviews written is stored in a PostgreSQL database.
Users are expected to register, while creating a secure password that will be hashed to a
database for adding an extra layer of security.

Website renders information via TMDB API (application programming interface). Currently
playing movies in Finland are rendered via Finnkino API. User interface has been designed with
simplicity, user-friendly and neutral tones, taking account design principles in accessibility.
This project is a graded assignment for group 7 in the course Advanced Web Applications
Project in Oulu University of Applied Sciences, taking place from October to December 2024.

## Technologies used

1. Programming language Javascript and its libraries
- Node.js, React.js
2. Cloud Services
- Azure, Supabase / AWS North
3. Database
- PostgreSQL
4. Version Control
- Git, GitHub
5. Project Management Methodology
- Agile, Kanban
6. Team members and responsibilities
- Yiling Chen : Full Stack development, database design, TMDB API data
- Eveliina Hampus : DevOps, Finnkino API data, Back End testing development, documentation
- Rahul Kalwar : Design, logo and Front End development
- Dominik Oslanec : Design, UI wireframes, CSS and responsiveness Front end development, documentation
- Shane Pruttinun : Full Stack development - extra feature, database design
- NuwanSundara Mudiyanselage : Project management, Full Stack and testing development.

## Architecture: Model-View-Controller

- The backend Model represents the Model. It handles business logic of the application. It
manages user data, and processing requests from the database.
- The frontend represents the View. It acts as a user interface and has been implemented
with React. It uses modular components like SearchBar, Header, Footer, authentication
forms, and UI elements for movies and reviews. Responsiveness has been implemented
with CSS.
- The Controllers have been implemented on the backend side for handling incoming
HTTP requests, processing them, interacting with the Model, and sending responses
back to the View.

Database structure

![database](https://github.com/movieapp-group7/.github/blob/main/database.png)

Interface description: UI design
Our approach focuses on creating a minimalistic and user-friendly interface that
ensures simplicity and quick navigation. Key features of the UI include:
- Intuitive Navigation: A consistent header and footer for seamless navigation.React Router integration for easy access to pages like profiles, movies, and
discussions.
- Responsive Design: Optimized layouts for various screen sizes using CSS.
- Interactive Components:Search Bar for refined movie searches. Authentication Forms for login and sign-up, ensuring security and ease of use.Dynamic Movie Display Cards with details, reviews, and discussion prompts.
- Theme:Clean and visually appealing design using soft colors and minimalistic aesthetics
to emphasize content.
- Accessibility:Designed with accessibility standards in mind (e.g., proper contrast).

UI Wireframe
![wireframe](https://github.com/movieapp-group7/.github/blob/main/Wireframe.jpg)


## Install and run locally
Prerequisite: Node.js installed, command line interface.
1. Create a directory for application
2. Move to the directory and clone both repositories `cd directory && git clone
https://github.com/movieapp-group7/movieApp || git clone
https://github.com/movieapp-group7/server`
3. Install dependencies with both repositories with `npm install`
4. Move to frontend repository and run `npm run start`
5. Move to backend repository and run `npm run devStart`

View on internet
Application is deployed on Azure, and will be viewable in:

[https://wonderful-sky-0dd374d10.4.azurestaticapps.net/](https://wonderful-sky-0dd374d10.4.azurestaticapps.net/)

