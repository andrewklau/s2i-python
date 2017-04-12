# Python S2I Docker images

[![Build Status](https://travis-ci.org/ausnimbus/s2i-python.svg?branch=master)](https://travis-ci.org/ausnimbus/s2i-python)
[![Docker Repository on Quay](https://quay.io/repository/ausnimbus/s2i-python/status "Docker Repository on Quay")](https://quay.io/repository/ausnimbus/s2i-python)

This repository contains the source for the [source-to-image](https://github.com/openshift/source-to-image)
builders used to deploy [Python applications](https://www.ausnimbus.com.au/languages/python/)
on [AusNimbus](https://www.ausnimbus.com.au/).

The builders are built using Python binaries from python.org

If you are interested in using SCL-based Python binaries, use [s2i-python-scl](https://github.com/ausnimbus/s2i-python-scl)

## Versions

The versions currently supported are:

- 2.7
- 3.6
