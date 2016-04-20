# docker-aptly
Docker image for aptly.

## Introduction
aptly is a Debian repository management tool. It simplifies the steps to mirror remote repositories, manage local package repositories, take snapshots, pull new versions of packages along with dependencies, and publish Debian repository.

For more information, check out https://www.aptly.info/

## Getting Started
* To pull: `docker pull isim/aptly`
* To build: `docker build --rm -t isim/aptly .`
* To run: `docker run --rm isim/aptly <aptly-command>`
* To serve the aptly API: `docker run -d -p 8080:8080 isim/aptly api server`

## License
Refer to the [LICENSE](LICENSE) file.
