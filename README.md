# Radix

[![Build Status](https://travis-ci.org/neffos-contrib/radix.svg)](https://travis-ci.org/neffos-contrib/radix)
![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/neffos-contrib/radix.svg)
[![GoDoc](https://godoc.org/github.com/neffos-contrib/radix?status.svg)][godoc]
[![Go Report Card](https://goreportcard.com/badge/github.com/neffos-contrib/radix/v3)](https://goreportcard.com/report/github.com/neffos-contrib/radix/v3)

Radix is a full-featured [Redis][redis] client for Go. See the [GoDoc][godoc]
for documentation and general usage examples.

## neffos-contrib

Contains temporarily fix for: https://github.com/mediocregopher/radix/issues/184. The import path of [neffos/stackexchange/redis](https://github.com/kataras/neffos/blob/master/stackexchange/redis/stackexchange_redis.go) didn't change, instead we use the [replace directive](https://github.com/golang/go/wiki/Modules#when-should-i-use-the-replace-directive) of the [go.mod](https://github.com/kataras/neffos/blob/master/go.mod#L5) file.

[redis]: http://redis.io
[godoc]: https://godoc.org/github.com/neffos-contrib/radix
