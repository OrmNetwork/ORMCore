
ORM Network
====

[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](https://choosealicense.com/licenses/isc/)
[![GoDoc](https://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/kaspanet/kaspad)

ORM Network is Kaspa fork representing decentralization with an improved black3P mining algorithm.

## What is ORM Network

ORM Network based on Kaspa, includes protection against ASICs, but allows mining on both GPU and CPU. The black3p algorithm we developed ensures that transactions are protected from tracking. In addition, the project does not currently have an explorer. We'll add it later to track the height of the block, but that's it.

## Requirements

Go 1.18 or later.

## Installation

#### Build from Source

- Install Go according to the installation instructions here:
  http://golang.org/doc/install

- Ensure Go was installed properly and is a supported version:

```bash
$ go version
```

- Run the following commands to obtain and install kaspad including all dependencies:

```bash
$ git clone https://github.com/OrmNetwork/ORMCore
$ cd ormcore
$ go install . ./cmd/...
```

- Ormcore (and utilities) should now be installed in `$(go env GOPATH)/bin`. If you did
  not already add the bin directory to your system path during Go installation,
  you are encouraged to do so now.


## Getting Started

Ormcore has several configuration options available to tweak how it runs, but all
of the basic operations work with zero configuration.

```bash
$ ormcore
```

## Discord
We create discord server soon

## Our Website and Roadmap
Website: https://ormnetwork.org


