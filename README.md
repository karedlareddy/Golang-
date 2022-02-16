# Golang-
package main

import (
	"fmt"
)

func main() {
	var fname, lname string = "John", "Doe"
	m, n, o := 1, 2, 3
	item, price := "Mobile", 4000

	fmt.Println(fname + lname)
	fmt.Println(m + n + o)
	fmt.Println(item, "_", price)
}
