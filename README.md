# Healthchecker

Healthchecker is a tiny command-line tool implemented in Go that checks whether a website or server is running or down by attempting TCP connections to specified domains and ports.

## Usage

1. Clone the repository to your local machine.
2. Navigate to the directory containing the project.
3. Run the main Go file (`go run main.go`) to start the health checking tool.
4. Use the following flags to customize the check:
    - `--domain` or `-d`: Specify the domain name to check (required).
    - `--port` or `-p`: Specify the port number to check (default is port 80).

Example usage:

```bash
$ go run main.go --domain example.com
