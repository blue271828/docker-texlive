# TeX Live Docker image

[![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/blue271828/texlive.svg)](https://hub.docker.com/r/blue271828/texlive)

This Docker image contains the full TeX Live packgage for Debian.



## Usage

This project provides container images on [Docker Hub](https://hub.docker.com/r/blue271828/texlive) .

```bash
$ docker pull blue271828/texlive
```



## Testing

You can test manually with the below command. This project is using dgoss (dgoss is docker wrapper around [Goss](https://github.com/aelsabbahy/goss)) for testing. Before deploying a new docker image to Docker Hub, [Automated builds](https://docs.docker.com/docker-hub/builds/) kicks this testing script.

```bash
$ docker-compose -f docker-compose.test.yml run sut
```
