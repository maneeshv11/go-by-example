#Values
Go has various value types including strings, integers, floats, booleans, etc. 
Here are a few basic examples.

## Program
```$xslt
package main

import "fmt"

func main()  {

	//comment

	fmt.Println("My name is " + "Maneesh")

	fmt.Println("1+1 is ", 1+1)

	fmt.Println("1+1.0 is ", 1+1.0)

	fmt.Println("7/3 is ", 7/3)

	fmt.Println("7/3.0 is ", 7/3.0)

	// boolean
	fmt.Println("true||false is ", true || false)
	fmt.Println("true && false is ", true && false)
	fmt.Println("!true is ", !true)

}
```

## Output
```$xslt
➜  values git:(go-values) ✗ go run values.go 
My name is Maneesh
1+1 is  2
1+1.0 is  2
7/3 is  2
7/3.0 is  2.3333333333333335
true||false is  true
true && false is  false
!true is  false
```



### Acknowledgments

* [Go by example](https://gobyexample.com)