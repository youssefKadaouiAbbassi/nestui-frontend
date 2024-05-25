
<h1 align="center">NestUI Frontend</h1>

## Overview
**NestUI Frontend** is the repository for the Docker configuration of the frontend of NestUI. 


## Prerequisites
- [Docker](https://www.docker.com/) should be installed on your system.

## Installation

### Steps
1. Clone the repository:
   ```bash
   git clone git@github.com:youssefKadaouiAbbassi/nestui-frontend.git
   ```
2. Change to the project directory:
   ```bash
   cd nestui-frontend
   ```

## Development Setup

### Building the Development Docker Image
```bash
make build-dev
```

### Starting the Development Docker Container
```bash
make start-dev
```

### Stopping the Development Docker Container
```bash
make stop-dev
```

## Production Setup

### Building the Production Docker Image
```bash
make build-prod
```

### Starting the Production Docker Container
```bash
make start-prod
```

### Stopping the Production Docker Container
```bash
make stop-prod
```

## Contributing
Contributions are welcome! Please read our [Contributing Guidelines](link-to-guidelines) for more information.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.