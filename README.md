# social-data-science-alliance.github.io
Website repository for the Social Data Science Alliance

Tech note: there are some files in this repository that aim to help you run a local Jekyll environment when editing content. These files should be excluded from deployment in `_config.yml`:
- Dockerfile
- Gemfile
- docker-compose.yml
In order to build the site you should be able to (after starting up Docker) `docker-compose build` then `docker-compose up`. When you're done, `docker-compose down`.
