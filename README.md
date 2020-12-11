# Puppeteer Docker Example

This as an example of using the Docker Puppeteer docker image to run Mocha tests against a linked Docker Compose web service, and capturing a screenshot into a local `./screenshots` directory.

## Running

```shell
# Build and run the example tests
docker pull tutum/hello-world
docker-compose -f docker-compose.linux-tests.yml run tests

# See the screen that was generated
ls screenshots/
```

## References

* [Puppeteer Troubleshooting](https://github.com/puppeteer/puppeteer/blob/main/docs/troubleshooting.md#troubleshooting)
* [buildkite/docker-puppeteer](https://github.com/buildkite/docker-puppeteer)