# Goat Craft

Pure AI slop, sorry.

---

## Local Development Guide

This guide explains how to run the project locally using Docker compose and Nginx. This setup does not require any IDE-specific extensions (like VS Code Live Server) and ensures consistency across different development environments.

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/) installed and running on your machine.

---

## Start the server

```bash
docker compose up -d
```

## Stop the server

```bash
docker compose down
```

---

## Accessing the Game

Once the container is running, open your web browser and navigate to: <http://localhost:8080>.

Any changes made to files in `public/` (such as `index.html`) are mounted live and will appear upon refreshing the browser.
