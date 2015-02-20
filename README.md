
# GopherLibTerminal - Go BearLibTerminal Bindings

This repository is a [Go](https://golang.org/) binding for the excellent [BearLibTerminal](http://foo.wyrd.name/en:bearlibterminal) library.

# Installing

## Requirements

It is required that [BearLibTerminal](http://foo.wyrd.name/en:bearlibterminal) is installed onto your system.

## Go Get

The usual `go get github.com/mpatraw/gopherlibterminal` should work.

# Usage

The official [reference](http://foo.wyrd.name/en:bearlibterminal:reference) for [BearLibTerminal](http://foo.wyrd.name/en:bearlibterminal) should serve as the main documentation. Renaming has been to honor [Go](https://golang.org/)'s naming convention. `terminal_open` becomes `gopherlibterminal.Open`.

I suggest you shorten "gopherlibterminal":

```
package main

import glt "github.com/mpatraw/gopherlibterminal"

func main() {
	glt.Open()
	glt.Print(0, 0, "Hello, world!")
	glt.Refresh()
	glt.Delay(1000)
	glt.Close()
}
```

# Documentation

See [BearLibTerminal](http://foo.wyrd.name/en:bearlibterminal)'s official [reference](http://foo.wyrd.name/en:bearlibterminal:reference).
