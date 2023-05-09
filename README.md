# Backend API
- Express, mongodb, node
#### Setup

```bash
npm install && npm start
```

#### Database Connection

1. Setup .env in the root
2. Add MONGO_URI with correct value

#### Player Model

1. name of the player (string, required)
2. why like the player (string, required, enum)
3. have user watched the player game before (boolean, required)

#### APIs

- POST /: Store form data into database. If successful, return the _id field generated by mongodb. 
- GET /: Return all user responses. 
- GET/{id}: Return a specific response. 

# Web application
- for first page, user can type in the name and will display all nba players with that name
- the public api is GET https://www.balldontlie.io/api/v1/players with query parameter search
