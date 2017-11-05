## React Client, Express Server Boilerplate

Scaffold a simple Express backend using express-generator, and a React frontend with create-react-app. Inside package.json under client, you’ll see the proxy key. That key must match the server, which is specified using PORT=3001 inside package.json under the server directory.

Backend -> Frontend connection based on this excellent blogpost from [Dave Ceddia](https://daveceddia.com/create-react-app-express-backend/).

#### To run:

```
$ cd client
$ yarn start
```

In a separate terminal window, kick off the server:

```
$ cd server
$ yarn start
```

#### TODO:
- Create fork for Redux state management
- Setup Jest testing for TDD workflow
- Introduce Flow? Typescript? Or just stick with PropTypes?

