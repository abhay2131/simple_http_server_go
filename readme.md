# Simple HTTP Server in Go

A basic HTTP server implementation in Go that demonstrates TCP connection handling and simple request processing.

## Description

This project implements a basic HTTP server that:

- Listens on port 1729
- Accepts TCP connections
- Simulates request processing with an 8-second delay
- Responds with "Hello, world!" to all requests
- Handles one connection at a time

## Features

- TCP connection handling
- Basic HTTP response
- Request processing simulation
- Simple error handling

## Getting Started

### Prerequisites

- Go 1.x or higher installed on your system

### Running the Server

1. Clone this repository
2. Navigate to the project directory
3. Run the server:

The server will start listening on port 1729.

### Testing the Server

You can test the server using:

- Web browser: Visit `http://localhost:1729`
- cURL:

## Limitations

- Handles only one connection at a time
- No request parsing
- Fixed response for all requests
- Basic error handling

## Future Improvements

- Add concurrent connection handling using goroutines
- Implement proper HTTP request parsing
- Add configurable response handling
- Improve error handling and logging
