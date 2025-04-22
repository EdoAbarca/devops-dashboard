## 🧠 Concept Overview – “DevOps Dashboard”
A web platform that acts like a **control center** for managing microservices in a simulated real dev environment. Think of it like a mini-Heroku + Grafana + CI panel mashup, with a clean UI.

---

## 🏗️ Core Features & Services (MVP-level)

| Feature | Service | Tech Ideas |
|--------|---------|------------|
| **User Auth + Projects** | `auth-service`, `projects-service` | JWT, RBAC, user > project ownership |
| **App Health Monitoring** | `monitoring-service` | Healthcheck pings, retry logic |
| **Live Logs Viewer** | `log-ws-service` | WebSocket + streaming logs |
| **Deploy Button + Status** | `deploy-simulator-service` | Deploy jobs (queued + tracked) |
| **Metrics Panel** | `metrics-service` | Request count, latency, uptime |
| **Web Dashboard** | `frontend-client` | Charts, logs and project management |

---

## 📦 Tech Stack

### 🖥️ Frontend
- `React` + `Tailwind CSS`
- WebSocket client
- Charting library: `Chart.js`

### 🔙 Backend (Microservices)
- **NestJS**
- **MongoDB**
- **Redis**
- **WebSocket Gateway**

### 🛠️ DevOps & Infra
- `Docker` & `docker-compose`
- `Pulumi`/`Terraform` for IaaC
- `CircleCI`/`GitHub Actions` for CI/CD
- `Nginx` reverse proxy (Still in evaluation)
- `Prometheus`

---

## 🔍 Project Showcase Focus Points

- Highlight **multi-service orchestration**
- Show off **Docker + infrastructure automation**
- Learning **WebSocket, metrics, and logs**
- Handling **task queues** and **CI/CD pipelines**
- This project mimics real DevOps workflows for managing apps and microservices ('mimics' shall be limited to demo purposes)
