# Docker Compose Example Files

Example docker compose files for running databases or emulators for local
development.

## Usage

Ensure you have `docker` and `docker-compose` installed properly. 

Run the following to spin up appropriately

```bash
# Spinning up docker-compose based on a file
docker-compose -f <file.yaml> up

# Example
docker-compose -f postgres.yaml up
```
