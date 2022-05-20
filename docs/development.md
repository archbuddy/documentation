# Development

## Organization of this product
This product is organized in 3 big repositories:
- Documentation: Generate this [documentation](https://github.com/archbuddy/documentation) that you are reading and hosts the [discussions](https://github.com/archbuddy/documentation/discussions) and [issues](https://github.com/archbuddy/documentation/issues) of all you
- Frontend: [React application](https://github.com/archbuddy/frontend) to show the graph an interact with people
- Backend: [Backend application](https://github.com/archbuddy/backend) to handle all the interactions

## Setup

Clone github projects

Go to the backend project:

```bash
docker-compose up
npm Install
npm run seed
npm start
```

Go to the frontend project:

```bash
npm Install
npm start
```

When asked for port conflit accept the new port and start development