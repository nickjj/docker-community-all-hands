Here's reference links to every talk I've given for the Docker Community All-Hands events.

### Best Practices around Creating a Production Ready Web App with Docker and Docker Compose

*March 11th 2021* 

In this talk we'll go over practical Docker Compose examples of using aliases &
anchors, creating a health check, using the override file pattern and making
the most of environment variables. On the Dockerfile side of things we'll go
over using multi-stage builds, running containers as a non-root user, using
build ARGs and an ENTRYPOINT script.

#### Example open source apps

- https://github.com/nickjj/docker-flask-example
  - The above link leads to the `main` branch (most up to date), but you can check out `0.4.0` to match the talk
- https://github.com/nickjj/docker-django-example
- https://github.com/nickjj/docker-rails-example
- https://github.com/nickjj/docker-node-example

#### Personal links / learning resources

- https://nickjanetakis.com
- https://diveintodocker.com
- https://runninginproduction.com
- https://nickjanetakis.com/courses/deploy-to-production

#### Blog post references

- https://nickjanetakis.com/blog/why-i-prefer-running-nginx-on-my-docker-host-instead-of-in-a-container
- https://nickjanetakis.com/blog/the-tools-i-use (every tool I used in the talk and how they're configured)
