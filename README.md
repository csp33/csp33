# Carlos Sánchez Páez

<p align="left">
  <strong>Data Platform Tech Lead @ <a href="https://feverup.com">Fever</a></strong> · Málaga, Spain<br/>
  <em>Building high-throughput real-time CDC platforms, distributed Kubernetes systems, and self-hosting my daily digital life on bare-metal.</em>
</p>

<p align="left">
  <a href="https://cspaez.org"><img src="https://img.shields.io/badge/Website-cspaez.org-059669?style=flat-square&logo=google-chrome&logoColor=white" alt="Website" /></a>
  <a href="https://cspaez.org/homelab"><img src="https://img.shields.io/badge/Homelab-Cluster%20Architecture%20%E2%86%97-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Homelab Architecture" /></a>
  <a href="https://linkedin.com/in/csp33"><img src="https://img.shields.io/badge/LinkedIn-in%2Fcsp33-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://medium.com/@csp33"><img src="https://img.shields.io/badge/Medium-@csp33-12100E?style=flat-square&logo=medium&logoColor=white" alt="Medium" /></a>
</p>

---

### 🏠 Self-Hosted Bare-Metal Homelab

I run a 24/7 production-grade 3-node physical Kubernetes cluster (`humberto`, `dosberto`, `tresberto`) that powers my personal cloud, IoT automations, and privacy stack ([Explore Architecture & Topology ↗](https://cspaez.org/homelab)):

- **Core Self-Hosted Services:**
  - 📸 **Photo & Media:** [Immich](https://immich.app/) (with hardware-accelerated ML), [Nextcloud](https://nextcloud.com/), [Jellyfin](https://jellyfin.org/) & automated media stack.
  - 🏡 **Home Automation & IoT:** [Home Assistant](https://www.home-assistant.io/), Zigbee2MQTT, Mosquitto MQTT broker.
  - 🔒 **Privacy & Security:** [Vaultwarden](https://github.com/dani-garcia/vaultwarden), AdGuard Home, Cloudflare Zero Trust Tunnels, Envoy Gateway & cert-manager.
- **Under the Hood:**
  - **GitOps Engine:** Managed declaratively via **Argo CD** sync-waves and Helm.
  - **Storage Fabric:** **Longhorn HA** replicated storage + **ZFS LocalPV** for high-IOPS CloudNativePG databases.
  - **Observability:** Centralized Grafana, Prometheus, Alloy, Loki logs, and Gatus status dashboard.

---

### ⚡ Enterprise Scale & Open Source

- 🚀 **Scaled Data Platform @ Fever (1 → 8):** Founding member & Tech Lead; architected Fever's modern data platform from the ground up.
- 📡 **Real-time CDC Streaming:** Engineered Kafka + Debezium + Tinybird architecture processing **300 TB/mo** and **1.5M+ req/mo** at **<50ms p99** ([Read Case Study ↗](https://www.tinybird.co/customer-stories/fever)).
- 🛠️ **Open Source:** Contributor to [Apache Airflow](https://github.com/apache/airflow) and [Spark on K8s](https://github.com/kubeflow/spark-operator); creator of [`cert-manager-duckdns-webhook`](https://github.com/csp33/cert-manager-duckdns-webhook) and [`terraform-provider-metabase`](https://github.com/csp33/terraform-provider-metabase) (Go).

---

### 🛠️ Tech Stack

#### Data Platform & Streaming
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

#### Homelab, Cloud & GitOps
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Home Assistant](https://img.shields.io/badge/Home%20Assistant-41BDF5?style=for-the-badge&logo=home-assistant&logoColor=white)
![Jellyfin](https://img.shields.io/badge/Jellyfin-00A4DC?style=for-the-badge&logo=jellyfin&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)

#### Languages & Backend
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Bash](https://img.shields.io/badge/GNU%20Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

---
