
# Docker Compose Apps

A collection of Docker Compose configurations for various applications. This repository aims to simplify the process of setting up and managing multiple services using Docker Compose.

## Table of Contents

- [Getting Started](#getting-started)
- [Available Applications](#available-applications)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with these Docker Compose configurations, clone this repository and navigate to the desired application's directory. Each application folder contains its own `docker-compose.yml` file and configuration instructions.

```bash
git clone https://github.com/Mafphp/docker-compose-apps.git
cd docker-compose-apps
```

## Available Applications

- **[App1](./app1)**: Brief description of the first application.
- **[App2](./app2)**: Brief description of the second application.
- **[App3](./app3)**: Brief description of the third application.

> **Note:** Each application's directory contains a README file with specific instructions on how to configure and run the service.

## Prerequisites

Before using any of the Docker Compose configurations, ensure you have the following installed on your machine:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Usage

1. **Navigate to the desired application's directory:**
    ```bash
    cd app1
    ```
   
2. **Start the service:**
    ```bash
    docker-compose up -d
    ```

3. **Stop the service:**
    ```bash
    docker-compose down
    ```

4. **Check the logs:**
    ```bash
    docker-compose logs -f
    ```

## Folder Structure

Each application has its own directory with the following structure:

```
app_name/
├── docker-compose.yml        # Docker Compose file for the application
├── .env                      # Environment variables (optional)
├── config/                   # Configuration files (if applicable)
└── README.md                 # Application-specific instructions
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License

This repository is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.
