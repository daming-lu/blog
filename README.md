# Paddle Blog

## Run locally

1. [Install Docker](https://docs.docker.com/docker-for-mac/install/)

1. Run the following command inside the repo directory:
    ```bash
    docker run --rm --privileged=true --label=jekyll --volume=$(pwd)/jekyll:/srv/jekyll --volume=$(pwd)/posts:/srv/jekyll/_posts jekyll/jekyll:3.5 jekyll serve -w
    ```

1. Open browser and visit http://localhost:4000
