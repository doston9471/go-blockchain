# Custom blockchain app in GO

## Setup

- `git clone https://github.com/doston9471/go-blockchain.git`
- `cd go-blockchain/`
- `mv .env.example .env`
- `go run main.go`

## Usage

- Go to `http://localhost:8080/`
- Send a `POST` request to `http://localhost:8080/` with a JSON payload with `BPM` as the key and an integer as the value.
For example:
```
{ "BPM":50 }
```

Send as many requests as you like and refresh your browser to see your blocks grow! Use your actual heart rate (Beats Per Minute) to track it over time.

## Result

<img width="1502" alt="result-screenshot" src="https://github.com/user-attachments/assets/7cea9db4-e0ad-4e5d-b4c8-69e0871e159d" />

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
