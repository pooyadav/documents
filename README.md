# DataBox
The Databox platform is an open-source personal networked device, augmented by cloud-hosted services, that collates, curates, and mediates access to an individual’s personal data by verified and audited third party applications and services. The Databox will form the heart of an individual’s personal data processing ecosystem, providing a platform for managing secure access to data and enabling authorised third parties to provide the owner with authenticated services, including services that may be accessed while roaming outside the home environment. Databox project is led by Dr. Hamed Haddadi (Imperial College) in collaboration with Dr. Richard Mortier (University of Cambridge) and Professors Derek McAuley, Tom Rodden, Chris Greenhalgh, and Andy Crabtree (University of Nottingham) and funded by EPSRC. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

1) Requires Docker. Read [here](https://docs.docker.com/engine/installation/) for docker installation.
2) Once docker is installed and running, install  docker-compose. Read [here](https://docs.docker.com/compose/install/) for installation. 
3) Requires Git (if it is not already on your machine). Read [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) for git installation.


### Installing
1) Clone Databox Git repo and run on your machine
```
        terminal$ git clone -b https://github.com/me-box/databox.git
```

```
     terminal$ cd databox
     terminal$ ./databox-start

### Operation

Once docker is installed, just run the following to get your databox up and
running using images published to <https://hub.docker.com/r/databoxsystems>:

    ./databox-start

Once it's started point a web browser at <https://127.0.0.1:8989> and have fun.

To stop databox and clean up,

    ./databox-stop

### Development

To develop on the platform and core components run

    ./databox-start dev

This will clones all the relevant repositories locally, and builds them into the
required Docker images. To try your component out, add your code into a
directory with a Databox manifest and `Dockerfile`, and then add a reference to
it in `docker-compose-dev-local-images.yaml`. Your image will then be built
alongside the platform. To install your app, upload the manifest to the local
app store on <http://127.0.0.1:8181> and it should then become visible in the
UI, ready for you to install.


### Running the tests

tbh

## Contributing

Please see the current [issues](https://github.com/me-box/databox/issues). [Fork](https://github.com/me-box/databox#fork-destination-box) the databox repo and fix bugs/issues and submit pull request. Read more on Fork and Pull [here](https://help.github.com/articles/fork-a-repo/).

## Versioning
tbh

## Authors

The list of [contributors](https://github.com/me-box/databox/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

 Databox has a number of platform components, detailed information about each can be found in their own  repositories:

* [Databox container manager](https://github.com/me-box/databox) 

* [databox-arbiter](https://github.com/me-box/databox-arbiter)

* [node-databox]( https://github.com/me-box/node-databox) nodejs lib for databox apps and drivers

* [databox-export-service](https://github.com/me-box/databox-export-service)

* [databox-store-blob](https://github.com/me-box/databox-store-blob) An example of the databox store API

* [databox-logstore](https://github.com/me-box/databox-logstore)

* [databox-app-server](https://github.com/me-box/databox-app-server) Server for storing and serving databox manifests 
