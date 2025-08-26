
# Complete Monitoring Stack for macOS

Docker Compose setup - Grafana, Loki, Alloy, Prometheus, Zeek, and Suricata for system monitoring and network security.

## Architecture

- **Grafana** (port 3000) - Visualization and dashboards
- **Prometheus** (port 9090) - Metrics collection
- **Loki** (port 3100) - Log aggregation  
- **Grafana Alloy** (port 12345) - Telemetry collection
- **Zeek** - Network security monitoring
- **Suricata** - Intrusion detection
- **Node Exporter** (port 9100) - System metrics
- **cAdvisor** (port 8080) - Container metrics



```bash
# Clone repository
git clone https://github.com/YOUR_USERNAME/zeekmonitoring-stack.git
cd zeekmonitoring-stack

# Run setup script
chmod +x setup.sh
./setup.sh

# Access Grafana
open http://localhost:3000
# Login: admin/admin123
