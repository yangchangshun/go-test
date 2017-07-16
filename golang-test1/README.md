编译go成为二进制
---
 
> go  build hello.go

通过指定参数编译成特定的平台
> * GOOS=linux go build -o hello.linux hello.go
> * GOOS=windoes go build -o hello.exe hello.go
> * GOOS=darwin go build -o hello.mac hello.go

