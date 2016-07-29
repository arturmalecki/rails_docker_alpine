# Example of smallest Rails 5 application

## Usage

### Build image

    docker build -t rails_alpine .

### Run container

    docker run -p 3001:3000 rails_alpine 

### Open this url

    http://localhost:3001

### Run bash in container

    docker run -i -t rails_alpine bash
