# demo-simple-express

A very simple node js app using express.

## How to run the project

- Locally,

  ```bash
  npm install
  npm run start
  ```

- or using docker container

  ```bash
  docker build -t demo-simple-express .
  docker run -d -p 8080:3000 demo-simple-express
  ```

- then access it on http://localhost:8080/

## LICENSE

This project and repository is under [MIT LICENSE](./LICENSE).
