# devops-k8s-pipeline-dem# 🚀 DevOps K8s CI/CD Pipeline with Monitoring

This project demonstrates a complete CI/CD pipeline setup using **Jenkins**, **Docker**, **Kubernetes**, and **Helm**, along with integrated monitoring using **Prometheus** and **Grafana**. It's designed to showcase production-grade DevOps skills including infrastructure as code, containerization, CI/CD, and observability.

---

## 📁 Project Structure

```
├── LICENSE
├── README.md
├── app/                     # Sample HTML web app + Dockerfile
│   ├── Dockerfile
│   └── index.html
├── helm-chart/              # Helm chart to deploy the app
│   ├── chart.yaml
│   ├── templates/
│   │   ├── deployment.yaml
│   │   ├── ingress.yaml
│   │   └── service.yaml
│   └── values.yaml
├── jenkins/                 # CI/CD Pipeline
│   └── Jenkinsfile
├── k8s/                     # Raw Kubernetes manifests
│   ├── configmap.yaml
│   ├── deployment.yaml
│   ├── ingress.yaml
│   └── service.yaml
├── monitoring/              # Prometheus & Grafana setup
│   ├── grafana-dashboard.json
│   └── prometheus.yaml
└── screenshots/             # UI screenshots (to be added)
```

---

## ⚙️ Tools & Technologies Used

| Tool/Platform  | Purpose                        |
|----------------|--------------------------------|
| Docker         | Containerization               |
| Kubernetes     | Orchestration                  |
| Helm           | K8s Deployment Automation      |
| Jenkins        | CI/CD Automation               |
| Prometheus     | Metrics collection             |
| Grafana        | Visualization and Alerting     |
| Ingress + Service | Load balancing & exposure |

---

## 📦 App Overview

- Simple static HTML app (`index.html`)
- Containerized with a `Dockerfile`
- Deployed via both:
  - Raw K8s YAML (`k8s/`)
  - Helm Chart (`helm-chart/`)

---

## 🛠 CI/CD Pipeline

- Written in `Jenkinsfile`
- Pipeline Steps:
  - Build Docker image
  - Push to Docker Hub
  - Deploy to Kubernetes using `kubectl` or `Helm`

---

## 📊 Monitoring & Observability

- **Prometheus** used for collecting metrics from Kubernetes
- **Grafana** for dashboards and alerts
- Preconfigured dashboard in `monitoring/grafana-dashboard.json`

---

## 🚧 Next Steps

- Add screenshots of Jenkins pipeline & Grafana dashboard
- Set up real-time cluster and deploy
- Setup Ingress with custom domain (optional)
- Add auto-scaling policies (HPA)

---

## 💼 Portfolio Value

This project is built to demonstrate:
- Hands-on Kubernetes
- CI/CD best practices
- Real-world DevOps workflows
- Monitoring & alerting setup
- Infrastructure as Code with Helm

---

## 👤 Author

**Ram Kumar**  
DevOps & Cloud Engineer  
📧 [aramkumarit@gamil.com]  
🔗 [LinkedIn Profile](#) | [GitHub](https://github.com/ram-codehub)

---

> ⭐ _Feel free to fork and use this as your learning reference or starter template._
o