# Liquidsoap Linting CI Example for Travi-CI

[![Build Status](https://travis-ci.org/radiorabe/travis-ex-docker-liquidsoap-linting.svg?branch=master)](https://travis-ci.org/radiorabe/travis-ex-docker-liquidsoap-linting)

This repo demonstrates how to lint a [liquidsoap](http://liquidsoap.fm) script on [travis-ci](https://travis-ci.org) using
the [CentOS](https://centos.org) based [RaBe Liquidsoap container image](https://github.com/radiorabe/docker-liquidsoap)
which is in itself based on the [RaBe Liquidsoap Distribution (RaBe-LSD)](https://github.com/radiorabe/centos-rpm-liquidsoap) for CentOS.

## Usage

Be inspired by this repos [.travis.yml](./travis.yml) and copy paste the parts you need to your own projects `.travis.yml`.

Have a look at this projects [travis page](https://travis-ci.org/radiorabe/travis-ex-docker-liquidsoap-linting) where we have
configured weekly build so there are always some recent builds. This can also help catch errors in liquidsoap
scripts at an early stage when the upstream docker image bump gets bumped to liquidsoap-next before we roll
the same update out to production.

## License
This example is free software: you can redistribute it and/or modify it
under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, version 3 of the License.

## Copyright
Copyright (c) 2018 [Radio Bern RaBe](http://www.rabe.ch)
