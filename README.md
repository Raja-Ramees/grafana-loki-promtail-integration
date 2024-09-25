# 🌟 Grafana-Loki-Promtail Integration 🚀

Welcome to the **Grafana-Loki-Promtail Integration** project! This setup enables seamless **log forwarding, aggregation, and visualization** using the following tools:

- 📜 **Promtail**: Collects and forwards logs.
- 📊 **Loki**: Stores and indexes logs.
- 📈 **Grafana**: Visualizes logs via customizable dashboards.

---

## 🔍 **Overview**

This project integrates **Promtail**, **Loki**, and **Grafana** to:

- 📥 **Forward logs** from servers using Promtail.
- 🗃️ **Store and aggregate logs** with Loki.
- 🖥️ **Visualize logs** in Grafana dashboards for real-time monitoring.

### 🔧 **Tools Involved**

- **Promtail**: Log collection agent.
- **Loki**: Log storage backend.
- **Grafana**: Visualization and dashboard creation.

---

## 📦 **Features**

- ✅ Centralized logging with **Promtail** and **Loki**.
- 🔍 Quick log search and filtering using **Grafana**.
- 📊 Prebuilt **dashboards** for easy visualization.
- ⚙️ **Customizable** log sources and retention policies.

---

## 📋 **Requirements**

Before you get started, make sure you have the following installed:

- 🐳 **Docker**
- 📦 **Docker Compose**
- 🖥️ **Git**

---

## 🚀 **Installation Steps**

### 1️⃣ Clone the repository:

```bash
git clone git@github.com:Raja-Ramees/grafana-loki-promtail-integration.git


2️⃣ Navigate to the project directory:
cd grafana-loki-promtail-integration


3️⃣ Set up and run the services using Docker Compose:
docker-compose up -d

⚙️ Configuration
Promtail:
Located in promtail-config.yml.
Modify log file paths or customize the scrape_configs section to include your log sources.
Loki:
Adjust settings in loki-config.yml for retention and performance tweaks.
Grafana:
Visit http://localhost:3000 and log in with the default credentials:

Username: admin
Password: admin
🎨 Dashboards
Import the predefined Loki dashboard into Grafana.
Visualize and monitor logs from all your sources in real time.
🛠️ Contributing
Feel free to open an issue or submit a pull request to enhance this integration!

📜 License
This project is licensed under the MIT License.

🌟 Happy Logging! 🌟




