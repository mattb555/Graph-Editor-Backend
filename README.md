# Graph Editor API 

Backend for Graph Editor, a Node Express app using Sequelize and GraphQL. All wrapped up in a docker image.

Demo site: https://grapheditor.orderandchaoscreative.com/

## Set Up

Grab repo: `git clone git@github.com:sarcoma/Graph-Editor-Backend.git`

Run docker compose: `docker-compose up --build`

### Initialise the DB

In the root of the API project run: `docker-compose exec web bash` to access the docker container.

Then go to the orm directory with: `cd src/orm`

Lastly run: `ts-node create-database.ts`

You should see the SQL queries printed to the terminal. Once they stop just hit `ctrl + c`.

This will create the database and insert some initial data.

## Frontend

The frontend can be found here: https://github.com/sarcoma/Graph-Editor
