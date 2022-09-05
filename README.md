# Belajar Go-Lang Dasar

## Tipe Data Integer (Signed)

1. int (Depends on platform 32bit system or 64bit system)
2. int8 (-128 to 127)
3. int16 (-32768 to 32767)
4. int32 (-2147483648 to 2147483647)
5. int64 (-9223372036854775808 to 9223372036854775807)

## Tipe Data Integer (UnSigned)

1. uint (Depends on platform 32bit system or 64bit system)
2. uint8 (0 to 255)
3. uint16 (0 to 65535)
4. uint32 (0 to 4294967295)
5. uint64 (0 to 18446744073709551615)

## Tipe Data Float

1. float32 (-3.4e+38 to 3.4e+38)
2. float64 (-1.7e+308 to +1.7e+308)

### Buat file type_number.go

```
package main

import "fmt"

func main() {
	fmt.Println("Satu = ", 1)
	fmt.Println("Dua = ", 2)
	fmt.Println("Tiga koma lima = ", 3.5)
}

```
