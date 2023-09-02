---
title: "Program Structure"
date: 2023-08-28T22:05:56+04:00
draft: false
---

## Create structure

1. Create folder for our program. Let's say it will be `go-program/`
2. In this directory do `go mod init go-program`
3. In this directory create `main.go` file

These are essential and common start for all Go programs.

## main.go

`main.go` contains `main()` function which is entry point for any Go programm.

The minimal `main.go` looks like:

```go 
package main

func main() {
    // code will be executed here
}
```

