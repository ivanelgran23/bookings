# Bookings

This is a sample project that demonstrates how to use the following technologies:

- Go
- Gin Web Framework
- Sessions with SCS
- Templating with Go Templates
- Package Management with Go Modules

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/ivanelgran23/bookings.git
```

2. Install dependencies:

```bash
cd bookings
go mod download
```

3. Start the server:

```bash
go run cmd/web/main.go
```

The server will be running on port 8080.

## Package Managers

This project uses the Go module manager to manage dependencies. The `go.mod` file contains the module declaration and specifies the dependencies for the project.

```
module github.com/ivanelgran23/bookings

go 1.21.6

require (
	github.com/alexedwards/scs/v2 v2.7.0
	github.com/go-chi/chi/v5 v5.0.12
	github.com/justinas/nosurf v1.1.1
)
```

## Technologies Used

- Go: The project is written in Go, a statically typed, compiled programming language designed at Google for building reliable and efficient systems.
- Gin: Gin is a web framework written in Go that is lightweight, fast, and flexible. It provides a simple, expressive, and elegant API for building RESTful APIs and web applications.
- Sessions with SCS: SCS (Secure Cookie Store) is a lightweight, fast, and secure session manager for Go web applications. It uses secure cookies to store session data, which helps to protect against session hijacking and other security threats.
- Templating with Go Templates: Go Templates are HTML templates that are optimized for performance and provide a simple, yet powerful, way to generate HTML output.
- Package Management with Go Modules: Go Modules is a new module system for the Go programming language. It is designed to provide accurate dependency versions, simplify vendoring, and improve the build process.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.