# A simple Golang HTTP load balancer

[![Build Status](https://travis-ci.org/intrip/golang-load-balancer.svg?branch=http)](https://travis-ci.org/intrip/golang-load-balancer)

A very simple HTTP load balancer written in Golang.

## Usage

```
$ cd {move_to}/golang-load-balancer
$ go get github.com/intrip/golang-load-balancer/common
$ go get github.com/spf13/viper
$ go build
$ ./golang-load-balancer
```

connect to http://localhost:8080 (default settings)

## Configuration

Edit `config.yaml` to customize your settings.
