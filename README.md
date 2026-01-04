# n8n-monitor

This project provides a monitoring stack for n8n using Docker Compose. It includes Prometheus for metrics collection and can be extended with other monitoring tools as needed.

## Structure
- `docker-compose.yml`: Docker Compose configuration for the monitoring stack.
- `prometheus/prometheus.yml`: Prometheus configuration file.

## Usage
1. Clone this repository.
2. Run `docker-compose up -d` to start the monitoring stack.
3. Access Prometheus and other services as configured.

## Customization
- Edit `prometheus/prometheus.yml` to add or modify scrape targets.
- Extend `docker-compose.yml` to add more monitoring or visualization services (e.g., Grafana).

## License
MIT License.
