# Go Conference Booking CLI

A simple command-line booking application written in **Go**.  
Users can enter their details, book tickets, and receive a simulated ticket confirmation.

## Features

- CLI user input (`fmt.Scan`)
- Input validation (name length, email contains `@`, ticket count in range)
- Stores bookings using a **struct + slice**
- Sends tickets asynchronously using **goroutines + sync.WaitGroup**

## Tech Used

- Go
- Goroutines
- `sync.WaitGroup`
- Basic string validation

## How to Run

1. Clone the repo
   ```bash
   git clone <your-repo-link>
   cd <repo-folder>
   ```

2. Run the program
   ```bash
   go run .
   ```

## Project Structure

```
.
├── go.mod
├── main.go
└── helper
    └── helper.go
```

## Example Output

```
Welcome to Go Conference booking application!
We have a total of 50 tickets and 50 are still available.
Get your tickets here to attend
Enter your first name:
...
```

## Notes
This project is designed to practice Go fundamentals such as:

- variables + constants
- slices and structs
- maps
- packages and imports
- concurrency with goroutines
