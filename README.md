# Animal Crossing Hub

## Story of application:

- The Animal Crossing Hub app will help users find villager, fossil, and critter information as well as vote for a most popular villager

#### Purpose of project:
To complete a Flatiron School Phase 2 project that met the following requirements:

- single page application using `create-react-app`
- include at least 5 components to implement well organized code
- include at least 3 client-side routes using React Router with a navigation bar
- use a `json-server` to create a RESTful API backend
- make at least one `GET` request and one `POST` request using a controlled form/component
- incorporate styling, such as CSS from scratch or use styled components

#### User will be able to:

- view the visiting villager on home page
- view the most popular villager and their information on villager page
- navigate to villager, fossil, and critter pages
- search and filter villagers and fossils
- upvote a villager
- view all villagers’ information on villager page
- view all fossils’ information on fossil page
- view all critters’ information on critter page

#### Challenges faced:

- implementing css to match Animal Crossing theme
- conditionally rendering seasonality data for critter page
- learning how to use React Modal
- reusing React components with different information rendered

#### Future implementation:

- enable user authentication and authorization for more restricted voting abilities
- enable users to leave comments per each villager

## Technologies

- React, HTML, CSS, JSON Server

## Installation

Run `npm install` to install packages and dependancies

Run `npm start` (TODO: get exact command) to start client side server and view application

Run `json-server --watch db.json` to create an api call using json server

## Usage
In webpage:

- initially loading the homepage should render a random generated villager available for upvoting
- initially loading the villager page should render the most popular villager, their information, ability to upvote them, the ability to filter villagers based on personality type, and search for villagers based on name
- initially loading the fossil page should render a *randomly generated featured fossil (TODO: check if this is the case)* with the ability to filter fossils based on *genus* and price
- initially loading the critters page should render a table of critter icons with the ability to filter by critter type, view each critter’s information, and conditionally render seasonality data

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Licenses

All resources used were free or open source used with the intention of creating an application inspired by the Animal Crossing made by Nintendo and MORE.
