## Kestra Enterprise Edition Examples

This repository provides code needed to PoC Kestra Enterprise Edition, including applications, dashboards, and flows. Use this repository as a starting point for setting up your environment and customizing it to your needs.

## Repository Structure
- **`apps/`**: contains verified Apps configuration as code
- **`dashboards/`**: provides examples of custom dashboards as code which you can use to build custom charts querying your executions, metrics and logs
- **`flows/`**: flow definitions
- **`docker-compose-example.yml`**: basic Docker Compose configuration for setting up the environment with Postgres backend. Use this file as a reference for running services locally in a containerized setup.

## Prerequisites

- Docker and Docker Compose installed
- Basic knowledge of Kestra and YAML 
- Kestra Enterprise Edition license

## Usage

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd eeexamples-main
   ```

2. **Set Up Docker Compose**:
   - Review and customize `docker-compose-example.yml` to match your environment.
   - Start the services:
     ```bash
     docker compose up -d
     ```

3. **Configure Flows, Apps or Dashboards**:
   - Add or modify flow definitions in the `flows/` directory.
   - Add or modify Apps configuration in the `apps/` directory.
   - Add or modify Dashboards configuration in the `dashboards/` directory.

## Contributing

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/<feature-name>
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add <feature-name>"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/<feature-name>
   ```
5. Open a Pull Request.

