# LaTeX Docker VS Code Template

A standardized environment for LaTeX document preparation using Docker and VS Code.

## Features

- Isolated LaTeX environment with Docker
- Pre-configured VS Code settings
- Consistent build process across different machines
- Volume-based TeX Live installation for package persistence
- SyncTeX support for forward/backward search
- Automatic PDF preview

## Prerequisites

- Docker and Docker Compose
- Visual Studio Code
- LaTeX Workshop extension for VS Code

## Getting Started

1. Clone this repository
2. Build the docker image: `cd .docker && docker-compose build`
4. Open the project in VS Code
5. Edit your LaTeX files in the `src` directory
6. Use LaTeX Workshop commands to build the document

## Directory Structure

- `.docker/`: Docker configuration files
- `.vscode/`: VS Code settings
- `latex/`: Contains all LaTeX-related files
  - `src/`: LaTeX source files
  - `output/`: Generated PDFs and auxiliary files
  - `figures/`: Image files for inclusion in the document
  - `include/`: Additional LaTeX files (chapters, bibliography, etc.)

## License

[MIT License](LICENSE)
