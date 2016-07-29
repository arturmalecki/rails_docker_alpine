# Example of smallest Rails 5 application Docker image

This is example for this [blog post](http://www.devcherry.com/?p=77&preview=true)

## Usage

### Build image

    docker build -t rails_alpine .

### Build image for default ruby image

    docker build -t rails_common -f DockerCommon .

### Run container

    docker run -p 3001:3000 rails_alpine 

### Open this url

    http://localhost:3001

### Run bash in container

    docker run -i -t rails_alpine bash
