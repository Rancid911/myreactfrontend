
# Social Network App

This repository contains the source code for a social networking application built with React and Node.js. Users can register, follow others, engage in chat conversations, and utilize a search feature to find messages.

## Getting Started

1. Clone the repository:

```bash
git clone https://eur01.safelinks.protection.outlook.com/?url=https%3A%2F%2Fgithub.com%2Fyour-username%2Fsocial-network-app.git&data=05%7C02%7Caivanov%40sisecam.com%7Cf790d06a4b2047d4388908dc127d7c61%7C4067565cd76c459abebf0d0a802924f8%7C0%7C0%7C638405577368467812%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C3000%7C%7C%7C&sdata=sjqOErYEYSnGfOigzGsiDBwMgSOd90SOS71w6tLp06M%3D&reserved=0
cd social-network-app
```

2. Install dependencies for both client and server:

```bash
# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install
```

3. Set up the database:

- Create a MongoDB database and update the connection string in `server/config/db.js`.

4. Configure environment variables:

- In the `client` directory, create a `.env` file and specify the appropriate environment variables.
- In the `server` directory, create a `.env` file with configurations such as `PORT` and `SECRET_KEY`.

## Running the Application

1. Start the server:

```bash
cd server
npm start
```

2. Start the client:

```bash
cd client
npm start
```

Visit `http://localhost:3000` in your browser to access the application.

## Features

- **User Registration:** Sign up for an account and create a profile.
- **Follow Functionality:** Connect with others by following their profiles.
- **Chat System:** Engage in real-time chat conversations with other users.
- **Message Search:** Utilize the search feature to find specific messages.

## Technologies Used

- **Frontend:** React, React Router, Context API, Axios, Socket.io
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)

## Contributing

Feel free to contribute by opening issues or submitting pull requests.

## License

No license
