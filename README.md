# Hosts

Simple utility to manage `/etc/hosts` file.

## Installation

```sh
go get -u github.com/zenwalker/hosts
```

## Examples

```sh
hosts add 127.0.0.1 example.com www.example.com
hosts rmhost www.example.com
hosts resolve example.com
hosts rmip 127.0.0.1
```

## Build

```sh
go build
```
