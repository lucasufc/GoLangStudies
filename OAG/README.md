# Aprenda Golang do Zero! Desenvolva uma APLICAÇÃO COMPLETA!
*Aprenda Go (Golang) do zero, 100% na prática e com uma aplicação real para colocar no seu portfólio de desenvolvedor!*

**Created by:** Otávio Augusto Gallego

**Udemy:** [Click Here](https://www.udemy.com/course/aprenda-golang-do-zero-desenvolva-uma-aplicacao-completa/?couponCode=KEEPLEARNING)


## 1 - Introduction
### 1.1 - Installation

On linux, run the command:
```bash
sudo apt install golang-go
```

You can check if it works running the command:
```bash
go version
```

For more information, visit the official GoLang website [here](https://go.dev/)

### 1.2 Hello World

To create an executable, follow these steps:

1. Reference the main package.
2. Import the libraries.
3. Create the main function.

At the end, your code should look like this:

```go
package main

import (
	"fmt"
)

func main() {
	fmt.Println("Hello, world!!!")
}

```

To run your code, you can use these commands:

1. `go run yourFile.go`
2. `go build yourFile.go && ./yourFile`