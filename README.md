# unicorns-ai-playground
This is a test repo for use with some tech folks to play with AI.

# Unicorns AI Playground

This repository is a sandbox for experimenting with **Dev Containers** and exploring **AI connectivity** using Python libraries. It is designed to help developers learn and experiment with containerized development environments while integrating AI tools and frameworks.

## Features

- **Dev Containers**: Pre-configured development environment using Docker and Visual Studio Code's Dev Containers.
- **Python Environment**: Includes Python setup with dependencies managed via `requirements.txt`.
- **OpenSearch Integration**: Automatically pulls and runs an OpenSearch container for testing AI-related data indexing and search capabilities.

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/) installed and running.
- [Visual Studio Code](https://code.visualstudio.com/) with the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers).

### Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/unicorns-ai-playground.git
   cd unicorns-ai-playground
1. Open the repository in Visual Studio Code.
1. When prompted, reopen the project in the Dev Container.
1. The container will automatically:
    1. Set up a Python environment.
    1. Pull and run an OpenSearch container.
1. Validate the setup by running:
    ```bash
    python validate_container.py
You should see the message: `Dev container validation test successful!`

## Project Structure
```
unicorns-ai-playground/
├── .devcontainer/          # Dev Container configuration files
│   └── devcontainer.json   # Main configuration for the Dev Container
├── .github/
│   └── dependabot.yml      # Configuration for Dependabot updates
├── Dockerfile              # Dockerfile for building the Python environment
├── requirements.txt        # Python dependencies
├── validate_container.py   # Script to validate the container setup
├── LICENSE                 # License file
├── README.md               # Project documentation
└── .gitignore              # Git ignore rules
```

## Using OpenSearch
The Dev Container automatically pulls and runs an OpenSearch instance. You can access it locally at:

API Endpoint: http://localhost:9200
Dashboard: http://localhost:9600
Default <vscode_annotation details='%5B%7B%22title%22%3A%22hardcoded-credentials%22%2C%22description%22%3A%22Embedding%20credentials%20in%20source%20code%20risks%20unauthorized%20access%22%7D%5D'> credentials</vscode_annotation>admin:
```
Username: admin
Password: SuperSecurePassword123!
```

## Contributing
This project is intended for learning and experimentation. Contributions are welcome! Feel free to open issues or submit pull requests.

License
This project is licensed under the MIT License.
Make sure to replace `SuperSecurePassword123!` with your actual desired password in both the `README.md` and the `devcontainer.json` file for consistency. Let me know if you need further adjustments!Make sure to replace `SuperSecurePassword123!` with your actual desired password in both the `README.md` and the `devcontainer.json` file for consistency. Let me know if you need further adjustments!