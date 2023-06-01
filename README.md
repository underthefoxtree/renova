# renova
re-no-va, from the latin word renovare, meaning "renew!" (to another person).

A simple and fast utility that updates your entire system, written in go.

## Requirements
- [`go`](https://go.dev/)

## Install
```bash
# Downlaod renova
go install github.com/underthefoxtree/renova@latest

# Install it in /usr/local/bin for sudo access
sudo renova install
```

## Usage
```bash
sudo renova
```

## Uninstall
```bash
# Remove the /usr/local/bin install
sudo renova uninstall

# Remove the go install (in $GOBIN)
renova uninstall
```
