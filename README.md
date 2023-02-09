# crypto-cupcakes
A Cupcake API using Auth0's OIDC for authentication and OAuth for authorization

## Getting Started

    npm i
    npm run start-dev
    npm install express express-openid-connect --save
    In .env:
    MY_SECRET = PUT_YOUR_OWN_SECRET_HERE
    CLIENT_ID = Auth0_provided_ID
    BASE_URL = http://localhost:3000
    AUTH0_DOMAIN = Auth0_provided_domain