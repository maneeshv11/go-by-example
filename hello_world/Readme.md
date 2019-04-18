# Hello World

The first program in go.

```$xslt
package main

import "fmt"

func main() {
	fmt.Println("Hello world!")
}
```

Running the go file.
* Using **go run**.
```$xslt
➜  hello_world git:(master) ✗ go run helloWorld.go
Hello world!
```

* Using **go build** like classic C. 

```$xslt
➜  hello_world git:(master) ✗ go build helloWorld.go
➜  hello_world git:(master) ✗ ls
Readme.md     helloWorld    helloWorld.go
➜  hello_world git:(master) ✗ ./helloWorld 
Hello world!
```

## Observations
* Package name should be **main** for directly running the go file.
* Every functions should be start with **func**
* The **main** method is the source of the program like **C**.


### Acknowledgments

* [Go by example](https://gobyexample.com)
