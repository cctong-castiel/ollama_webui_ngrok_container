# Ollama Web UI Docker Setup

This repository provides a simple way to deploy Ollama Web UI along with Ngrok and Nginx using Docker Compose. With this setup, you can securely access the Ollama Web UI from anywhere using an Ngrok link. Leverage LLM models to answer your questions on the go.

<img src="drawing.jpg" alt="Ollama Web UI Architecture" width="300"/>

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/)

### Usage

Start all services:

```bash
docker-compose up -d
```

Stop all services:

```bash
docker-compose down
```

Once started, check your terminal for the Ngrok forwarding URL to access the Ollama Web UI remotely.

### Next actions
- Apply more configuration settings in nginx and ngrok.

## References

- [Ollama Web UI Docker GitHub Repo](https://github.com/codearrangertoo/ollama-webui-docker)
- [Getting Started with Ngrok](https://ngrok.com/docs/guides/developer-preview/getting-started/)
- [Using Ngrok with Docker](https://ngrok.com/docs/using-ngrok-with/docker/)
- [How to Use Ngrok With Docker](https://tech.aufomm.com/how-to-use-ngrok-with-docker/)
- [Agent Config Version 3](https://ngrok.com/docs/agent/config/v3/#agent-configuration)
- [ngrok-docker GitHub Repo](https://github.com/thinhdanggroup/ngrok-docker/tree/main)

---

Feel free to open issues or submit pull requests for improvements!