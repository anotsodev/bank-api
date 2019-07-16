# Bank API

Bank API is just a simple django project and was made just to play with the basic and advanced stuff in django-rest-framework.

## Installation

You need the following software to fire up this bad boi:

- Docker
- docker-compose

### Docker

We'll use Docker to build the Bank API including its dependencies for easier management and deployment.

### docker-compose

We'll use docker-compose to pull necessary images including web server and database and other things to make this application app and running. You may costumize the docker-compose file if you want to use other web server or want this web application to use load balancers.

## Usage

```sh
# make sure that docker and docker-compose are installed
# just run the command below to build and deploy the Bank API

docker-compose build 
docker-compose up -d

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
