# Belajar Go-Lang Dasar

## Tipe Data String

### Tipe data string diisi dengan "(tanda petik dua) dan diakhiri dengan "(tanda petik dua lagi)

## Fungsi untuk Tipe Data String

1. len("string") => Untuk menghitung jumlah karakter
2. "string"[number] => Untuk mengambil karakter pada posisi yang ditentukan

### Buat file string.go

```
package main

import "fmt"

func main() {
	fmt.Println("Ini adalah Tipe Data String")

	// Fungsi di String
	fmt.Println(len("Ini berjumlah 16"))

	// Result bilangan bit
	fmt.Println("Aku adalah Rimuru"[0])
	fmt.Println("Aku adalah Rimuru"[1])
}
```
