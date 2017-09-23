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
        terminal$ git clone -b development  https://github.com/me-box/databox.git
```

```
     terminal$ cd databox
     terminal$ ./start
```

And repeat

```
until finished
`

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
 files in the repository are general development guides and specs. Databox has a number of platform components, detailed information about each can be found in their own  repositories:

* [Databox container manager](https://github.com/me-box/databox) 

* [databox-arbiter](https://github.com/me-box/databox-arbiter)

* [node-databox]( https://github.com/me-box/node-databox) nodejs lib for databox apps and drivers

* [databox-export-service](https://github.com/me-box/databox-export-service)

* [databox-store-blob](https://github.com/me-box/databox-store-blob) An example of the databox store API

* [databox-logstore](https://github.com/me-box/databox-logstore)

* [databox-app-server](https://github.com/me-box/databox-app-server) Server for storing and serving databox manifests 
