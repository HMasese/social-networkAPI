# social-networkAPI
![Static Badge](https://img.shields.io/badge/License-MIT-green)

## Description

- **Motivation**: The motivation behind this project is to create a scalable and efficient backend for a social network application. The goal is to provide users with a seamless experience in connecting, sharing thoughts, and reacting to content while ensuring data consistency and integrity.Key motivations include:Learning and implementing CRUD operations with MongoDB and Mongoose,Understanding RESTful API development using Node.js and Express, Practicing database relationships by linking users, thoughts, and reactions, Implementing automated data cleanup, such as deleting associated thoughts when a user is removed, Testing API endpoints using Insomnia to ensure functionality before integrating with a frontend.
- **Why build This Project**: This project was built to practice and implement **backend development concepts** using **MongoDB, Express, and Node.js**. The goal was to create a **scalable and efficient API** that allows users to interact with a social network-like system where they can add friends, share thoughts, and react to others' thoughts.  
- **What problem's did it solve**: Provides a structured way to handle user interactions, friendships, and reactions within a social network, Simplifies database management by ensuring user deletions clean up related thoughts, Enables seamless API testing using Insomnia, allowing easy debugging and improvements.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Features](#features)
- [How to Contribute](#how-to-contribute)
- [Tests](#tests)
- [Questions](#questions)
- [Links](#links)

## Installation
```
git clone git@github.com:HMasese/social-networkAPI.git
cd SocialNetworkAPI

npm install

MONGODB_URI=mongodb://localhost:27017/socialNetworkDB
PORT=3001

npm start
```

## Usage
- Clone the repo, install dependencies, and start the server.
- Use Insomnia or Postman to test API endpoints.
- Extend functionalities by adding authentication (e.g., JWT) or additional features.

## Credits
phil, dylan, aley, sidhuad

## License
A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code. https://choosealicense.com/licenses/mit/

## Features
- Add authentication (JWT) for user security.
- Implement pagination for large datasets.
- Enhance error handling with detailed messages.

## How to Contribute
clone the Repo, fork it push changes and other bug fixes and ill approve the merge request's.

## Tests
```
- Use Insomnia to send API requests and test functionality.
- JSON format should be used for all POST and PUT requests.
```

## Questions
For Further Questions and Bug reports Please reach out to me at Github (https://github.com/HMasese) or email me at harrietm616@gmail.com

## Links
- [video Demo]
- [Repository](https://github.com/HMasese/social-networkAPI)
