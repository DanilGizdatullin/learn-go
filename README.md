# Learn Go

## Introduction

### 1. Compiling Files

```shell
go build greet.go
```

to run the code

```shell
./greet
```

### 2. Running Files

```shell
go run greet.go
```

`go run` does not create an executable file. 

### 3. Packages

`package main` - declaration that file is executable. It means this program will be compiled into an executable.

`import "fmt"` - example of package importing.

```go
import "package1"
import "package2"

or

import (
    "package1"
    "package2"
)

or 

import (
    p1 "package1"
    "package2"
)

// example of using

p1.SampleFunc()
```

### 4. Comments

Line comments:

```go
// This entire line is ignored by the compiler
// fmt.Println("Does NOT print")
fmt.Println("This gets printed!") // This part gets ignored
```

Block comments:

```go
/*
This is ignored.
This is also ignored.
fmt.Println("This WON'T print!")
*/
```

### 5. Go Doc

```shell
go doc fmt
go doc fmt.Println
```

