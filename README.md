# kai

kai is a minimalist one‑liner for instantly sharing any local folder over HTTP. It prints a scannable ASCII‑art QR code and the URL pointing to a temporary web server running on a random free port of your machine.

## Principle

Launches a silent http.server (Python ≥ 3.7) rooted at the chosen directory.

Prints an ASCII QR code that encodes http://<your‑ip>:<port> plus the plain URL.

Runs until you hit Ctrl‑C.

## How to use

### Share the current directory
./kai

### Share a specific path
./kai /path/to/folder

