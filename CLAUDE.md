# eraser

Open-source Go CLI (Cobra, SQLite history, YAML config) that sends GDPR/CCPA data-removal requests
to data brokers, with a web UI under `internal/web`. `README.md` describes setup, configuration and
the broker flow; `./eraser --help` lists the commands. Build with `go build -o eraser ./cmd/eraser`,
test with `go test ./...`.

User configs (`config.yaml`) hold personal data: they are gitignored and the loader refuses one
readable by others.
