# Golang Course Curriculum

## Module 1: Introduction to Go
- Introduction to Go and its use cases  
- Setting up Go environment (Go SDK, VSCode/GoLand)  
- Go workspace and project structure  
- First Go program: “Hello, World”  
- Go commands (`go run`, `go build`, `go mod`, `go install`)

## Module 2: Go Basics
- Variables and Constants  
- Data Types (int, float, string, bool)  
- Type Conversion and Aliases  
- Operators and Expressions  
- Control Structures:
  - `if`, `else`
  - `switch`, `fallthrough`
  - `for` loops (traditional and range-based)

## Module 3: Functions in Go
- Defining and invoking functions  
- Parameters and return values  
- Variadic functions  
- Named return values  
- Recursion  
- Anonymous functions and closures  
- `defer`, `panic`, and `recover`

## Module 4: Arrays, Slices, and Maps
- Arrays and multidimensional arrays  
- Slices (creation, capacity, copy, append)  
- Slice tricks and best practices  
- Maps (creation, CRUD, loops)  
- Structs and Nested Structs

## Module 5: Pointers and Methods
- Introduction to pointers  
- Value types vs Reference types  
- Struct methods and pointer receivers  
- Method overloading (Go style)

## Module 6: Interfaces and Composition
- Introduction to interfaces  
- Interface implementation  
- Empty interface (`interface{}`) and Type Assertions  
- Interface embedding and polymorphism  
- Composition vs Inheritance

## Module 7: Packages and Modules
- Creating and using packages  
- Go modules (`go mod init`, `go mod tidy`)  
- Import paths and package visibility  
- Standard Library overview

## Module 8: Concurrency in Go
- Goroutines  
- Channels (unbuffered, buffered, directional)  
- `select` statement  
- WaitGroups and Mutexes (sync package)  
- `context` package for goroutine control

## Module 9: Error Handling
- Built-in error handling (`error` interface)  
- Custom error types  
- Wrapping and unwrapping errors (Go 1.13+)  
- Best practices

## Module 10: Working with Files and I/O
- Reading and writing files  
- Working with `bufio`, `os`, `ioutil`, and `filepath`  
- JSON and CSV parsing

## Module 11: Building Web Applications (REST API)
- HTTP server using `net/http`  
- Routes and Handlers  
- Handling Query Parameters and Path Variables  
- Working with JSON Requests and Responses  
- Creating RESTful endpoints (CRUD)  
- Using third-party routers (e.g., Chi, Gorilla Mux, Fiber)

## Module 12: Databases in Go
- SQL Database (PostgreSQL, MySQL, or SQLite)  
- Using `database/sql` and `sqlx`  
- Connecting, querying, inserting, updating  
- Using connection pools  
- Struct Mapping and Scanning rows  
- ORM introduction (GORM)

## Module 13: Testing in Go
- Writing unit tests with `testing` package  
- Table-driven tests  
- Benchmarking and profiling  
- Mocks and interfaces  
- Integration testing

## Module 14: Building Real-World Projects
- Task Management API  
- Blog or Forum Backend  
- Book-keeping App  
- Simple Chat System using Goroutines and Channels

## Module 15: Deployment and DevOps Basics
- Environment variables and config files  
- Building and compiling binaries  
- Dockerizing Go applications  
- Basic CI/CD with GitHub Actions  
- Hosting on platforms (Render, Railway, DigitalOcean, etc.)

## Module 16: Advanced Topics (Optional)
- Generics in Go  
- Reflection in Go  
- Plugin system  
- WebSockets in Go  
- Microservices and gRPC (with Protobuf)
