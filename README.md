# cypress-example-docker-compose-included
> Example showing `docker-compose` running local Cypress tests inside a container using [cypress/included][included] image

See [docker-compose.yml](docker-compose.yml) file

## Use

```shell
# run tests using built-in Electron browser
docker-compose run e2e-electron

# run tests using Chrome browser pre-installed in cypress/included image
docker-compose run e2e-chrome
```

[included]: https://github.com/cypress-io/cypress-docker-images/tree/master/included#cypressincluded

## Examples

Find more Docker + Cypress examples in [Cypress Docker docs](https://on.cypress.io/docker)
