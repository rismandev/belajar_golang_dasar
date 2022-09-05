# Belajar Go-Lang Dasar

## Deklarasi Variable

### Kata kunci var
```
var name string
name = "Rimuru Tempest"
```

### Mengisi nilai default
```
var name = "Rimuru Tempest"
```

### Tanpa menggunakan kata kunci var (:=)
```
name := "Rimuru Tempest"
```

## Deklarasi Multiple Variable
```
var (
	firstName = "Rimuru"
	lastName = "Tempest"
)
```

## Buat file variable.go
```
package main

import "fmt"

func main() {
	var name string

	name = "Rimuru Tempest"
	fmt.Println(name)

	name = "Benimaru"
	fmt.Println(name)

	var age = 18
	fmt.Println(age)

	gender := "Male"
	fmt.Println(gender)

	var (
		firstName = "Rimuru"
		lastName  = "Tempest"
	)
	fmt.Println(firstName)
	fmt.Println(lastName)
}

```
