
Ubuntu 32-bit Image with Runit Supervisor
-----------------------------------------

This image extends the 32-bit Ubuntu core with the [*runit* service supervisor daemon](http://smarden.org/runit/) packages from the Ubuntu repositories.

As a service supervisor *runit* is easy to use, reliable, small and fast. 

### Depends On

[ubuntu32](https://hub.docker.com/r/f69m/ubuntu32/)

### Usage

This image is hardly useful on its own, but allows derived images to run services simply by adding a script under `/etc/services`. However it can be started as is to twiddle its thumbs till stopped:

    $ docker pull f69m/ubuntu32-runit
    $ docker run --rm f69m/ubuntu32-runit

