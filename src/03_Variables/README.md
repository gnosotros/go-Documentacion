# Variables

Las variables son valores que pueden ir cambiando en diversas partes del codigo
segun como lo especifiques, pero gastan mas recursos que las
[constantes](./../02_Constantes).

Las variables se pueden declarar de varias formas:

```go
func main() {
	primeraForma := 1 //Bastante Parecida a Python
    	var segundaForma = 2 //Como en JavaScript
	var terceraForma int16 = 3 // Parecido a C++
}
```

Pero la forma que menos recursos gasta es la 3ra siendo la que especifica mas
cosas y ahorra mas trabajo al compilador.

<div align="center">
<a href="https://youtu.be/a5NYAK-TXXE"><img src="./../../img/03-min.png"/></a>
</div>

## Otra forma de declarar variables 

También se puede realizar la declaración de variables en grupos de forma declarativa e iterativa.

### variables

```html
var <name> <type> = <value>
or
<name> <type> := <value>
```


```go
package main

import "fmt"

func main() {

	// Declaracion de constantes
	const pi float64 = 3.14
	const pi2 = 3.1415

	fmt.Println("pi", pi)
	fmt.Println("pi2", pi2)

	// Declaracion de variables entera
	var area int        //normal
	var altura int = 14 // iterativa
	base := 12          // iterativa

	fmt.Println("area", area)
	fmt.Println("altura", altura)
	fmt.Println("base:", base)

	//Forma en grupo
	var (
		i int
		h bool
		s string
	)

	i = 1
	h = true
	s = "un texto cualquiera"

	fmt.Println(i)
	fmt.Println(h)
	fmt.Println(s)

	x1, y2, z3 := 1, 2, 3
	fmt.Println(x1)
	fmt.Println(y2)
	fmt.Println(z3)
	
}
```

## Continua la lectura:

- [Capitulo Anterior: Constantes](./../02_Constantes)

- [Capitulo Siguiente: Zero Values](./../04_Zero-Values)
