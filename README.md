# Belajar Go-Lang Dasar

## Membuat Hello World App

### 1. Buat file hello_world.go

```
package main

import "fmt"

func main() {
	fmt.Println("Hello World")
}
```

### 2. Jalankan Hello World App (Dengan Compiler)

```
go build hello_world.go && ./hello_world
```

### 3. Jalankan Hello World App (Tanpa Compiler)
Note : Tidak disarankan ketika deployment ke server.

```
go run hello_world.go
```