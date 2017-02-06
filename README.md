[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/cowsay.svg)](https://hub.docker.com/r/rubygem/cowsay/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/cowsay.svg)](https://hub.docker.com/r/rubygem/cowsay/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/cowsay.svg)](https://hub.docker.com/r/rubygem/cowsay/)
[![Gem Downloads](https://img.shields.io/gem/dt/cowsay.svg)](https://rubygems.org/gems/cowsay/)
# cowsay

Auto-Generated Docker image for cowsay to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/cowsay`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/cowsay`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/cowsay`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/cowsay/)
