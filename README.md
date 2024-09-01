# WordPress Docker Project

This project manages multiple WordPress instances using Docker containers.

## Project Structure

```
wordpress_docker_project/
├── config/
│   ├── nginx.conf
│   ├── php.ini
│   └── wp-config.php
├── docker/
│   └── Dockerfile
├── docs/
│   ├── server_environment.md
│   ├── docker_setup.md
│   ├── wordpress_instances.md
│   └── ...
├── scripts/
│   ├── backup.sh
│   └── deploy.sh
├── docker-compose.yml
├── .gitignore
└── README.md
```

## Setup

1. Ensure Docker and Docker Compose are installed on your system.
2. Clone this repository.
3. Configure the environment variables in `docker-compose.yml`.
4. Run `docker-compose up -d` to start the containers.

## Documentation

Detailed documentation for various aspects of the project can be found in the `docs/` directory.

## Scripts

- `scripts/backup.sh`: Use this script to create backups of your WordPress instances and databases.
- `scripts/deploy.sh`: This script facilitates the deployment process for updates and new instances.

## Configuration

Configuration files for Nginx, PHP, and WordPress can be found in the `config/` directory. Adjust these as needed for your specific setup.

## Contributing

Join this wonderful Project

## License

MIT License 2024 Guntram Bechtold
