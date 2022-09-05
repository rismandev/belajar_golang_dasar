# Belajar Go-Lang Dasar

## Variable Constant

### Deklarasi Variable Constant
```
const firstName string = "Rimuru"
const lastName = "Tempest"
```

### Deklarasi Multiple Variable Constant
```
const (
	firstName = "Rimuru"
	lastName = "Tempest"
)
```

### Nilai Variable Constant tidak dapat diubah
```
const (
	firstName = "Rimuru"
	lastName = "Tempest"
)

// Error
firstName = "Veldanava"
lastName = "Milim"
```

## Buat file constant.go
```
package main

import "fmt"

func main() {
	// const firstName string = "Rimuru"
	// const lastName = "Tempest"
	// const age = 18

	// Multiple Declaration
	const (
		firstName = "Rimuru"
		lastName  = "Tempest"
		age       = 10
	)

	// Error,
	// Nilai constant tidak dapat diubah
	// firstName = "Veldanava"
	// age = 24

	fmt.Println(firstName)
	fmt.Println(lastName)
	fmt.Println(age)
}
```