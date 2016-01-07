# hashstructure

hashstructure is a Go library for creating a unique hash value
for arbitrary values in Go.

This can be used to key values in a hash (for use in a map, set, etc.)
that are complex. The most common use case is comparing two values without
sending data across the network, caching values locally (de-dup), and so on.

## Installation

Standard `go get`:

```
$ go get github.com/mitchellh/hashstructure
```

## Usage & Example

For usage and examples see the [Godoc](http://godoc.org/github.com/mitchellh/hashstructure).
