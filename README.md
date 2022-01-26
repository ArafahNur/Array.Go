#Array.Go

package main

import (
	"fmt"
)

func main() {
	var arr [3][3]int
	arr[0][0] = 1
	arr[0][1] = 2
	arr[0][2] = 5
	arr[1][0] = 3
	arr[1][1] = 4
	arr[1][2] = 7
	arr[2][0] = 6
	arr[2][1] = 9
	arr[2][2] = 8
	fmt.Print(" ", arr[2][2])
	fmt.Print(" ", arr[2][1])
	fmt.Print(" ", arr[2][0])
	fmt.Print(" ", arr[1][2])
	fmt.Print(" ", arr[1][1])
	fmt.Print(" ", arr[1][0])
	fmt.Print(" ", arr[0][2])
	fmt.Print(" ", arr[0][1])
	fmt.Print(" ", arr[0][0])
}
