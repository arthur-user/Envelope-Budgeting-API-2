# Personal Budget API 2 📃📃
A Node.js API using the Express framework with the purpose of calculating daily budget expenditure with the means of envelope budgeting. Users are able to create, read, update, delete (CRUD), as well as create transactions for individual envelopes. Envelope data is persisted in a database through PostgreSQL.

## Running the application:
To locally run the application, Node.js needs to be installed. Install the required dependencies through npm install. Initiate the server through npm run start.

Once the application is running locally, the documentation may be accessed at http://localhost:5432/api/v1/api-docs

##Using Swagger to test:
Available Swagger tests:

# Envelopes:
Get all envelopes: GET /api/v1/envelopes
Get single envelope: GET /api/v1/envelopes/{id}
Create an envelope: POST /api/v1/envelopes
Update an envelope: PUT /api/v1/envelope/{id}
Delete an envelope: DELETE /api/v1/envelope/{id}
Create an envelope transaction: POST /api/v1/envelope/{id}
#Transactions:
Retrieve all transactions: GET /api/v1/transactions
Retrieve a single transaction: GET /api/v1/transactions/{id}
Update a transaction: PUT /api/v1/transactions/{id}
Delete an envelope: DELETE /api/v1/transactions/{id}
## Possible extensions for the API:
To bolster user security, add authentication and authorization
Establish a new API endpoint where users can add a single balance that's shared across several envelopes
## Possible dependency issues: 🚩
Please check the appropriate versions of the Node modules used in package.json. The Node modules are included within the node_modules folder.
