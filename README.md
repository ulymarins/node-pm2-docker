# Node and PM2 Dockerized

Just a small boilerplate developed to simplify the creation of new projects using Node, PM2 and Docker.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Docker

### Main commands

Build image
```
$ docker build -t <your username>/node-pm2-docker .
```

List images
```
$ docker images
```

Run images
```
$ docker run -p 49160:8080 -d <your username>/node-pm2-docker
```

Get container ID
```
$ docker ps
```

App output
```
$ docker logs <container id>
```

Run commands inside the container
```
$ docker exec -it <container id> /bin/bash
```

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

* **Ulysses Marins** - *Initial work* - [ulymarins](https://github.com/ulymarins)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
