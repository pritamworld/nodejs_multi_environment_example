# nodejs_multi_environment_example

## To build and properly tag the Docker image execute the following command:
- docker build . -t ghcr.io/<YOUR_GITHUB_USERNAME>/node-express:prod

## Once the build is over, you can run a container using the image locally to validate everything is working as expected running:
- docker run -p 3000:3000 ghcr.io/<YOUR_GITHUB_USERNAME>/node-express:prod

# References
- https://www.koyeb.com/tutorials/deploy-a-node-express-application-to-production