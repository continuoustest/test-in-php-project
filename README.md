# Test locally

You can use docker container to simulate the environement

```
# Start selenium
docker-compose up -d selenium

# Launch codeception test inside a php7.0 container
docker-compose up codeception
```