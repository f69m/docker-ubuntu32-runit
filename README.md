
Ubuntu 32-bit Image with runit Supervisor
-----------------------------------------

This image extends the 32-bit Ubuntu core with the [runit service supervisor daemon](http://smarden.org/runit/) packages from the Ubuntu repositories.

As a service supervisor runit is easy to use, reliable, small and fast.

### Depends On

  * [f69m/ubuntu32](https://hub.docker.com/r/f69m/ubuntu32/)

### Installation

The latest build of this image can readily be pulled from Docker Hub:

```console
$ docker pull f69m/ubuntu32-runit
```

### Usage

This image is hardly useful on its own, but allows derived images to run services simply by adding a script under `/etc/services`. However it can be started as is to twiddle its thumbs till stopped:

```console
$ docker run -d --name runit f69m/ubuntu32-runit
```

### Contribute

You are welcome to discuss this image, report issues or contribute changes on Github or leave comments on Docker Hub.

  * [f69m/ubuntu32-runit](https://hub.docker.com/r/f69m/ubuntu32-runit/) on Docker Hub
  * [f69m/docker-ubuntu32-runit](https://github.com/f69m/docker-ubuntu32-runit/) on Github

