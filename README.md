# MeetEase
MeetEase is a web application that allows users to easily schedule and manage online meetings. With MeetEase, users can create and share their availability, send meeting invitations, and receive confirmations, all in one place. MeetEase helps users save time and stay organized by streamlining the meeting scheduling process, and provides a convenient way to connect with colleagues, clients, and friends from anywhere in the world.

## Features

- **Authentication:** The project includes JWT-based authentication to secure user data.
- **Authorization:** The project includes role-based authorization to restrict access to certain routes or functionality.
- **Cross-platform compatibility:** The project is designed to be compatible across multiple platforms and devices.
- **Hashing:** User passwords are securely hashed to protect against unauthorized access.
- **dotenv:** The project uses `dotenv` to manage environment variables and sensitive configuration data.
- **Relationship:** The project includes database schema relationships between collections to support complex data structures.
- **Aggregation:** The project uses MongoDB's aggregation framework to perform advanced queries and data manipulations.

## Tech Stack

**Client:** HTML, CSS, JavaScript 

**Server:** Node.js, Express.js, Socket.io

**Database:** MongoDB, Redis

## Run Locally

Clone the project

```bash
  git clone https://github.com/chetandabli/busy-motion-6100
```

Go to the project directory

```bash
  cd busy-motion-6100
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  node index.js
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`privateKey` secret key for jwt token

`rprivateKey` secret key for jwt refresh token

`redisClientPassword` redis client password

`redisClientHostlink` redis client host link

`redisClientHost` redis client host

## Demo
https://busy-motion-6100-production.up.railway.app/

## Authors

- [@chetandabli](https://github.com/chetandabli)
- [@kuldeep55567](https://github.com/kuldeep55567)
- [@KeertiPawar8](https://github.com/KeertiPawar8)
- [@ujjwal1309](https://github.com/ujjwal1309)
    
    WORKFLOW =>
    ...........
    
![meetease-data-relatioship](https://user-images.githubusercontent.com/107751849/229445013-7b309b18-2043-4178-86e6-c2b126499cea.png)


HomePage, Video Calling => Kuldeep Tiwari
Checking meeting for user and deploying, logout => Chetan Ram
Appointments => Keerti pawar
login => ujjwal
    
    deploy link :-
    railway (https://busy-motion-6100-production.up.railway.app/)
