# Development

If you want to contribute you are in the right page

## Organization of this product

This product is organized in 3 big repositories:

- Documentation: Generate this [documentation](https://github.com/archbuddy/documentation) that you are reading and hosts the [discussions](https://github.com/archbuddy/documentation/discussions) and [issues](https://github.com/archbuddy/documentation/issues) of all you
- Frontend: [React application](https://github.com/archbuddy/frontend) to show the graph an interact with people
- Backend: [Backend application](https://github.com/archbuddy/backend) to handle all the interactions

## Setup

### Setup mongo

Option 1, just use the docker-compose file running `docker-compose up` that will start the mongo server and the mongo express explorer

Option 2, install mongodb locally following instruction from <https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-os-x/>
Some quick commands:

- brew services start mongodb/brew/mongodb-community
- brew services stop mongodb/brew/mongodb-community
- brew services list

### Application
Clone github projects

Go to the backend project:

```bash
npm Install
npm run seed
npm start
```

Go to the frontend project:

```bash
npm Install
npm start
```
