# Cypress Docker Django Next.js

Basic example of testing a Full Stack application with Cypress inside of Docker.

See the corresponding blog post: https://johnnymetz.com/posts/dockerize-your-cypress-tests/

## Docker

### `cypress run` in Docker

```
make cypress-run-docker
```

### `cypress open` in Docker

Setup X server. Follow the instructions outlined [here](https://dev.johnnymetz.com/posts/dockerize-your-cypress-tests/#setup-x-server).

```
make cypress-open-docker
```

## Host

### `cypress run` on Host

```
make cypress-run-host
```

### `cypress open` on Host

```
make cypress-open-host
```
